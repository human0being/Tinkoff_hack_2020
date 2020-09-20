# Tinkoff Hack 2020
## DeepHunch Team

The main idea is creating of **Tinkoff Adventures** - pack of quests and challenges, which will be personalized for each customer, based on his or her transactions, social status and the way of living. With this feature stong integration with Tinkoff ecosystem can be created, which will lead to encreasing bank working capital and clients can save money, using additional cashback.

Technical implementation of **Tinkoff Adventures** consists of four main parts:

1. Improving baseline working model by extending the number of features to provide better quality of predictions for future transaction of cliens. Realisation - ```.\baseline_improvement``` 

2. Predicting income of clients in future using history of transactions as features. Our pipline in Notebook one slightly changes baseline to collect income of clients from provided dataset and to train model predicting single real number using MSE loss for training. Realization can be found in ```.\outcome_prediction```.

3. Making use of predictions collected by previous two models in parts 1 and 2 and create decision rule, which recommends customer certain activities based on predicted transactions and taking into account possible income. Realisation  - ```./recommend_activity```

4. Using stories content to extract information on customers intetrest on travels to recomend them preferable tours. Implementation of prototype ```./stories_recommendation```

Further improvements:
- predictions quality;
- connection with stories;
- composition of quests from suggested activities;

HackLab course, Skoltech

Love Runs The World :)
