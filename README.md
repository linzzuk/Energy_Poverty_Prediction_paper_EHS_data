# Machine Learning with Administrative Data for Energy Poverty Identification in the UK


This repository contains the code and data for the paper **"Machine Learning with Administrative Data for Energy Poverty Identification in the UK"**. The research explores how machine learning models can leverage adminisative and survey data to improve energy poverty assessment in the UK.

## Repository Structure
```
Energy_Poverty_Prediction_Paper_EHS_Data/
│── plots_of_results/                # Directory for storing visualization results
│── raw_data_EHS/                    # Raw data files from the English Housing Survey
│── .gitignore                        # Ignore list for Git
│── clean_data.csv                    # Processed dataset for model training
│── data_pre_process.ipynb            # Notebook for data preprocessing
│── ep_prediction_model.ipynb         # Notebook for energy poverty prediction modeling
│── LICENSE                            # License information
│── performance_metric_result.csv      # Model performance results
│── README.md                          # Project documentation
```

## Dependencies
Make sure to install the required Python packages before running the code:

```bash
pip install pandas numpy scikit-learn xgboost matplotlib seaborn
```

## How to Use
1. **Preprocess Data**: Run `data_pre_process.ipynb` to orgise raw datasets and calculate LIHC indicator.
2. **Train Models**: Use `ep_prediction_model.ipynb` to train machine learning models and evaluate performance.
3. **Analyze Results**: Check the output in `performance_metric_result.csv` and visualiation are in `plots_of_results/`.

## Key Features
- **Energy Poverty Identification**: Utilizes machine learning to classify households at risk of energy poverty.
- **Multiple Model Selection**: Includes model selections for handling imbalancing issue.
- **XGBoost Model Optimization**: Includes hyperparameter tuning for improved accuracy.
- **Feature Engineering**: Incorporates administrative and socioeconomic data to enhance prediction performance.
- **SHAP Analysis**: Provides interpretability insights into the model’s predictions.

## Citation
If you use this work, please cite:

```
@article{Lin Zheng 2025,
  title={Machine Learning with Administrative Data for Energy Poverty Identification in the UK},
  author={Lin Zheng and Eoghan McKenna},
  journal={Energies},
  year={2025}
}
```
If you have any quesitons, plesse contact lin.z@ucl.ac.uk
## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

