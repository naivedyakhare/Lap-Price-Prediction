README FOR LAPTOP PRICE PREDICTOR

// Libraries \\
Pandas
seaborn
Matplotlib (for plotting various graphs)
numpy
sklearn (To import the model for training: Random Forest Regressor)
streamlit (For lap price predictor interface to enter values)

// Brief Info \\
Creating a laptop price predictor we use an ensemble model, Random Forest Regressor, that combines the randomforest and regression to
predict laptop price from the provided specifications like Processor, RAM, Pixels, etc, and hosting the predictor using streamlit on the
temporary local server.

// STEPS \\
1) Import all the above mentioned libraries.
2) Open the CSV file containing the data and store it into a variable.
3) Work on the data by either removing unwanted attributes having no affect on the price or by changing the model enough for it to fit 
   into the model.
4) Train.
5) Create streamlit interface to enter the details of the laptop specifications whose price is to be predicted.

// PRECAUTION \\
- Do not enter the value 0 in any of the field as it WILL give error.
// Submitted by - Naivedya Khare \\
