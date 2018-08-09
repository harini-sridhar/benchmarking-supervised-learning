# Benchmarking Supervised Algorithms on a large repository  

## Description
From Penn benchmark datasets at https://github.com/EpistasisLab/penn-ml-benchmarks, 166 datasets are downloaded. Six Supervised Learning models are used to analyze these datasets -  
1. Decision Tree  
2. Random Forest  
3. Extra Trees  
4. Gradient Boost  
5. AdaBoost  
6. XGBoost  

Multiprocessing is used to run the models faster due to the large data.  
The accuracy of each algorithm is compared with the others' and the performance is plotted using a heat map.    

## Starting the Project

This project contains these files:

- `benchmark.ipynb`: This is the main project file.
- `scores.p`: Pickle file containing the accuracy of all the methods for all datasets.  
- `result.png`: The accuracy comparison heat map.
