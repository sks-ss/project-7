# Language Translator (English - French)
This project uses sequence to sequence model of recurrent neural network to translate any piece of English text to French. I have used recurrent nets because while training on huge data, recurrent nets actually predict the outcome a lot better than any normal machine learning models. In this specific model, the data first passes through an encoder, comes out as an understanding and passes to a decoder. The decoder generates the output.

## Installation
To run this project, following library need to be installed inside a local virtual environment

```
conda install numpy
conda install pandas
conda install matplotlib
conda install tensorflow
```
## Running the project
To run this project, first download the notebook file(.ipynb) and extract it. Then set up your conda virtual environment. You may take help from interet for how to setup conda virtual environment.

once you set up virtual enviroment. start the notebook by running the following command in Command prompt(windows).
```
activate environment_name
jupyter notebook
```
You will be redirected to a browser tab. Navigate to the notebook file location through the notebook browser and open it.



#### * Virtual enviornment will be setup and activated for you

##### ** (If not activated, use the following command) **

```
source venv/bin/activate
```
Install the required packages using the following command.
```
pip install -r requirements.txt
```

## Train the project

```
python run_me.py
```

![Terminal screen_1](https://github.com/Satyaki0924/language-translation-english-to-french/blob/master/res/lt1.png?raw=true "Terminal1")

##### ** Choose 1 to train **

![Terminal screen_2](https://github.com/Satyaki0924/language-translation-english-to-french/blob/master/res/lt2.png?raw=true "Terminal2")

![Terminal screen_3](https://github.com/Satyaki0924/language-translation-english-to-french/blob/master/res/lt3.png?raw=true "Terminal4")

## Test the project
Run the python file, following the instructions

```
python run_me.py
```

The outcome should look something like this:

![Terminal screen_4](https://github.com/Satyaki0924/language-translation-english-to-french/blob/master/res/lt4.png?raw=true "Terminal4")

## Plotting the graphs

#### ** If the training goes well, the graphs should look something like this **

![Plot](https://github.com/Satyaki0924/language-translation-english-to-french/blob/master/res/plot.png?raw=true "Plot")

### Author: Sanjeev kumar
#### *** This project is strictly for educational purposes only. **
