# Capstone_project
Predictive Maintenance for aircraft engine using FD0001 dataset from NASA repository.

The model implementation involves dimension reduction technique UMAP with Deep LSTM model. It consist of the comparative study with the other state of the art approaches and 
the result shows that using UMAP dimension reduction helps in improving the RUL predictive for the aircraft engine.

Two dimension reduction techniques (PCA and UMAP) have been compared and UMAP which is novel approach has outperformed the PCA. Deep LSTM model ahs been used for making the time series prediction. The customized data preparation has been performed with different sequence length of the time window to feed the LSTM model to predict the remainining useful life of the engine.

Sliding window approach with sequnce length = 50 has given the best results.
