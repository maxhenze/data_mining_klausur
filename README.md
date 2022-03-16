# About
This project trys to replicate the results of the paper : "CONTEXT-SENSITIVE VISUALIZATION OF DEEP LEARNING NATURAL LANGUAGE PROCESSING MODELS" by Dunn et al. Furthermore it is an
exam for the lectre: Data Mining, held in the 2021/22 winter semester at the Martin-Luther-University.

# Using this Repository 
The overall complexity of using this repository for own research purposes is not to high. 

## Requirements

- a working version of Python 3.8.10 (other versions might work too)

## Installation 

1. clone the repository to the desired location 
2. run `pip install -r requirements.txt` for fetching all the needed packages 
3. run all cells of the `main.ipynb` Jupyter Notebook

## Customizations

- Hyperparameters can be set in a seperate cell.
- Also an option to choose, wether a new model should be trained or an existing should be used, is given.
- Model training was done on an external GPU. Tensorflow which it recognizes. Thus, usage of CPU is very likely to happen for most users. This will result in longer training times.
  - GPU usage can be achieved by installing the corresponding GPU drivers. (CUDA etc.)

## Known Problems

- At least upon using the Project on Windows Problems can occure when loading the BERT model. These can be fixed by deleting the content of the `Temp` folder found under `/AppData/Local`.
