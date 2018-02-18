# SMS-Classification
Classify SMS as spam or ham, based on the Kaggle challenge.

Link: https://www.kaggle.com/uciml/sms-spam-collection-dataset

**Context** </br>
The SMS Spam Collection is a set of SMS tagged messages that have been collected for SMS Spam research. It contains one set of SMS messages in English of 5,574 messages, tagged acording being ham (legitimate) or spam.

**Content**</br> The files contain one message per line. Each line is composed by two columns: v1 contains the label (ham or spam) and v2 contains the raw text.

**Inspiration** </br> Use this dataset to build a prediction model that will accurately classify SMS.

## Architecture
* A 100 dimensional Embedding layer
* 1 densely connected layer 32 hidden units, relu activation
* 1 output layer, sigmoid activation
