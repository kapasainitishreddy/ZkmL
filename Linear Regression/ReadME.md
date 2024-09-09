# Zero-Knowledge Proof with Machine Learning Model

This repository demonstrates how to convert a machine learning model into a format suitable for zero-knowledge proofs (ZKPs) using the `ezkl` library. The process includes creating a simple linear regression model, exporting it to the ONNX format, calibrating it, compiling it, and then generating and verifying a zero-knowledge proof.

## Overview

The code performs the following tasks:

1. **Dependency Management**: Checks if the notebook is running in Google Colab and installs necessary packages.
2. **Model Creation**: Defines and trains a linear regression model using scikit-learn.
3. **Model Conversion**: Converts the trained model into a PyTorch model and exports it to ONNX format.
4. **Data Preparation**: Prepares input and output data for ZKP operations.
5. **Model Calibration and Compilation**: Calibrates and compiles the model for ZKP.
6. **Proof Generation and Verification**: Generates and verifies a zero-knowledge proof.

## Prerequisites

Before running the code, make sure you have the following dependencies installed:

- `ezkl`: For zero-knowledge proof operations.
- `onnx`: For handling ONNX models.
- `hummingbird-ml`: For converting machine learning models.

You can install these dependencies using pip:

```bash
pip install ezkl onnx hummingbird-ml
