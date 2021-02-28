# English to UNL (Interlingua) Enconversion
A system to convert English sentences into expressions of an interlingua called Universal Networking Language (UNL). UNL represents knowledge in form of semantic network, where nodes represent concepts and links represent semantic roles between concepts. UNL nodes also contain semantic attributes like number, tense, aspect, mood, negation etc. 

## Example
English sentence- John worked specially for the social fund.

[UNL representation] agt(work.@past.@entry, John), man(work.@past.@entry, specially), pur(work.@past.@entry, fund), mod(fund, social)

Here agt (agent), man (manner of the action), pur (purpose) and mod (modifier) are the UNL relations.

## Requirements
1. python-3
2. pandas
3. numpy
4. nltk
5. spacy (python -m spacy download en_core_web_sm)
6.  

## Inputs
1. dictionary.csv - vocabulary with attributes
2. commonwords.csv - custom list of stop words
3. reldict.csv
4. attr_data_en.json - attributes
5. dict2.csv - Exceptional words dictionary
6. Dictionary_excep.csv - Exceptional words dictionary
