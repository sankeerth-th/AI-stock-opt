# AI-stock-opt
AI Project on stock portfolio optimization

This repository contains a Double Deep Q-Network (DDQN) trading agent, which uses Reinforcement Learning (RL) to make stock trading decisions. The agent learns to maximize its profit by choosing the optimal actions (buy, hold, or sell) based on historical stock price data.

**Features**

. Utilizes a DDQN agent to predict optimal trading actions

. Preprocessing of stock data

. Visualization of buy and sell signals on a stock price chart

. Saving and loading trained agents

. Model training with EarlyStopping and ModelCheckpoint callbacks

**Requirements**

. Python 3.7 or higher

. TensorFlow 2.5 or higher

. Pandas

. Numpy

. Matplotlib

. Scikit-learn

**Usage**

. Clone this repository to your local machine.

. Install the required dependencies.

. Add your stock data in CSV format to the project directory. The CSV file should contain columns: 'open', 'high', 'low', 'close', and 'volume'.

. Update the filename variable in the main() function with the name of your CSV file.

. Run the script using python script_name.py in your terminal.

. The agent will be trained for the specified number of episodes, and the results will be plotted and displayed.

. Buy and sell signals will be generated, and a chart will be displayed with these signals overlaid on the stock price.

. The trained agent will be saved to a file and can be loaded for future use.

**Customization**

. To change the number of episodes the agent is trained for, modify the episodes variable in the main() function.

. To change the window size used for the agent's state, modify the window_size variable in the main() function.

. To adjust the agent's hyperparameters (e.g., memory size, learning rate, etc.), modify the corresponding variables in the DQNAgent class definition.

**Contributing**

. If you'd like to contribute to this project, please submit a pull request with your proposed changes. Ensure that your changes are well-documented and follow the existing code style.
