
# Autonomous Robot Navigation (Cat) using Reinforcement Learning

## Project Overview

This project simulates a reinforcement learning environment called **Cat Quest**, where a custom environment is built using the `Gymnasium` library. The agent (a cat) interacts with the environment to reach certain goals (like catching fish, avoiding traps) while being rewarded or penalized. 

The environment is rendered using `Matplotlib` and the game dynamics are designed using `Gymnasium`.

## Technology Stack

- **Python**: Programming language for backend logic.
- **Gymnasium (gym)**: Used for building custom reinforcement learning environments.
- **Matplotlib**: For visualizing the environment grid.
- **NumPy**: For numerical operations and managing game state.
- **Jupyter Notebook**: For interactive development and testing of the environment.

## Project Structure

- `CatQuestEnvironmentfile.ipynb`: Jupyter notebook that contains the implementation of the custom environment and its simulation.
- `Images/`: Folder containing images used for rendering the environment.
- `.gitignore`: File specifying which files/folders to ignore in Git.
- `Related Questions.pdf`: Document containing related questions or explanations.

## Installation Instructions

### Prerequisites

- Python 3.x
- Jupyter Notebook (for running the notebook file)

### Steps

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd Cat-Quest-Environment-Using-Reinforcement-Learning
   ```

2. Create and activate a virtual environment (optional but recommended):

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required dependencies:

   ```bash
   pip install gymnasium matplotlib numpy
   ```

4. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open the `CatQuestEnvironmentfile.ipynb` notebook to explore and run the environment simulation.

## Usage

Once you have installed the required packages and launched the Jupyter Notebook, you can simulate the Cat Quest environment by running the cells in the notebook. The environment will render visually, allowing you to see the cat's actions and rewards.
