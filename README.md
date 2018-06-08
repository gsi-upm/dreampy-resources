# dreampy-resources
Resources for the paper "How well do Spaniards sleep? Analysis of Sleep Disorders based on Twitter mining"

# Data
Datasets described in the paper are liberated.
Due to [Twitter](https://www.twitter.com) relatively new [Developer Agreement and Policy](https://developer.twitter.com/en/developer-terms/agreement-and-policy), only the tweets IDs are shared.
The tweets data can be retrieved again.
This process is known as _hydrating_ a tweet.

## Insomnia Dataset
The data is in `insomniaDataset.csv`.
Annotations are: `y` for positive class (suffering insomnia), and `n` for negative class (not suffering insomnia).

## Themes and Symptoms Dataset
The data is in `themesDataset.csv`.
Annotations are encoded as follows:

Themes:
- a) User expresses only his sleep disorder.
- b) User expresses his sleep disorder and gives the causes of his problem.
- c) User expresses his or her disorder and requests help.
- d) User expresses his sleep disorder and transmits what he does at night.
- e) User expresses his/her sleep disorder and takes some action to try to solve it.

Symptoms:
- a) Difficulty in starting sleep
- b) Short sleep duration
- c) Difficulty in sleeping and low energy during the next day
- d) No Symptom

---
# Ackowledgements
Spanish Ministry of Economy and Competitiveness under the R&D projects SEMOLA (TEC2015-68284-R),
ITEA3 EmoSpaces (ITEA3-14012/RTC-2016-5053-7) and project ITEA3 SoMeDi (ITEA3-15011).
