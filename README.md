This project uses a Linear Regression model to predict house prices based on features like square footage, number of bedrooms, and number of full bathrooms. It includes both a command-line version and a Tkinter-based GUI.

FILES INCLUDED:
| File Name                     | Description                                               |
| ----------------------------- | --------------------------------------------------------- |
| `train.csv`                   | Training dataset (from Kaggle’s House Prices competition) |
| `test.csv`                    | Test dataset used for prediction                          |
| `house_price_prediction.py`   | Main script to train the model and make predictions       |
| `house_price.py`              | GUI application built with Tkinter                        |
| `house_price_predictions.csv` | Output file containing predicted prices on test data      |
| `README.md`                   | Project documentation (you are here!)                     |

Features Used:
GrLivArea – Above ground living area (in sq ft)

BedroomAbvGr – Number of bedrooms above ground

FullBath – Number of full bathrooms

Technologies Used:
Python 3.x

Scikit-learn

Pandas

Tkinter (for GUI)

Matplotlib (for visualization)

📊 Model Output

The linear regression model achieves an R² score of ~0.58 with basic features. You can improve accuracy by engineering additional features from the dataset.
