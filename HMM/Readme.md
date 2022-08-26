## Hidden Markov Rule

#### What is hidden markov rule (HMM)?

#### Let's take an example

![](images/main.jpg)

- In this diagram let's say we only get to see observation and we have to predict the present state.
- The probabilities between one hidden state to another hidden state is called **transition probability**.
![](images/transition.jpg)
- The probability between states and observation is called **emission probability**.
![](images/emission.jpg)

#### Some questions?
- How do we find these probabilities?
- How to find probability that random day is sunny or rainy?
- If given output is happy today, What is the probability that it's sunny or rainy?
- If for 3 days output mood is Happy, Sad, Happy what is the weather?

#### 1. How do we find these probabilities?
From past data.

**Transition Probability**

Image shows past 15 days data arranged in order
![](images/past_data_transition.jpg)

Given this data lets calculate transition proability
![](images/transition_proba.jpg)

**Emission Probability**

Image shows past 15 days data weather associated with mood arranged in order
![](images/emission.jpgjpg)

Given this data lets calculate transition proability
![](images/emissison_proba.jpg)


#### 2. What is the probability of random day is sunny or rainy?
Let's say mood is not given what is the probability of sunny or rainy?

#### 3. Given that we are happy what is the probability of sunny or rainy?
IMAGE

## 4.

