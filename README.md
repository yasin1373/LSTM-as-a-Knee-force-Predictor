# Knee Force Predictor

This project implements a deep learning model to predict knee joint forces during a squat exercise based on electromyography (EMG) data. It utilizes Long Short-Term Memory (LSTM) networks to capture temporal relationships in the multivariate time series input data.

## Problem Statement 

Understanding knee joint biomechanics during dynamic exercises like squats is important for injury prevention and sports performance. Directly measuring knee forces requires invasive instrumentation. This project explores a data-driven approach to predict knee forces using muscle activation patterns.

## Data

The data consists of EMG readings from 16 lower body muscles along with simultaneously recorded knee forces during squat exercises. The EMG data captures the temporal patterns of muscle activations while the knee force provides the prediction target.

## Methods

- Data preprocessing steps like normalization and train/test splitting
- LSTM network with 4 memory units to learn temporal relationships  
- Mean squared error loss function and Adam optimizer
- Performance evaluation with root mean squared error (RMSE) on train and test sets

## Results

The model achieves low prediction errors on both train and test data, demonstrating its ability to effectively learn the mapping from muscle EMG patterns to net knee force.

## Usage

The Jupyter notebook provides full code to reproduce the analysis. The required input data files are also included.

The model can be integrated into biomechanics applications to estimate knee joint forces based on easily obtained EMG data. This enables non-invasive monitoring of knee loading during exercise.

