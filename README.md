## FIEGNN
Code of our paper "[Feature Interactions Enhanced Graph Neural 
Networks Recommendation Model for Corporate Volunteer Activities]"

## Requirements
* Python==3.10.4
* pytorch==1.12.1
* pandas==2.0.2
* numpy==1.25.0
* cuda=10.2

## Directory

- code

  model.py: Model function

  train.py: Train function

- data
  
  ics_all.dat、ics_test.dat、ics_train.dat、ics_val.dat: Interactive dataset
  
  neighbor_aspect_extension_2_zscore_ics_uuii_0.20_10.pkl: Dataset of Neighbors and Their Attributes

  uiinfo.pkl: Statistical data table

  item_entity_embedding.npy、user_entity_embedding.npy：Embedding vectors for item and user
  
