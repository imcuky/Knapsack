# Knapsack Problem Empirical Study

This project is an empirical study of the Knapsack Problem, a combinatorial optimization problem. The goal is to determine which items to include in a collection so that the total weight is less than or equal to a given capacity and the total value is as large as possible.

## Algorithms Implemented

1. **Generate and Test (Brute Force)**
2. **Greedy Algorithm**
3. **Simulated Annealing**
4. **Genetic Algorithm**

## Dataset

The dataset used for this study was retrieved from Kaggle, created by Chirag Chauhan. It includes:
- Weights of the items
- Prices of the items
- Capacity of the knapsack
- Best combination of items
- Expected optimal solution

## Setup Instructions

1. **Clone the repository:**
    ```bash
    git clone https://github.com/imcuky/Knapsack.git
    ```

2. **Navigate to the project directory:**
    ```bash
    cd Knapsack
    ```

3. **Install the required libraries:**
    ```bash
    pip install pandas numpy matplotlib
    ```

4. **Open the Jupyter Notebook:**
    ```bash
    jupyter notebook KNAPSACK_PROBLEM.ipynb
    ```

## Usage

1. **Import Libraries:**
    The necessary libraries such as pandas, numpy, matplotlib, etc., are imported at the beginning of the notebook.

2. **Read Dataset:**
    The dataset is read from a CSV file hosted on GitHub.

3. **Preprocessing:**
    The dataset is preprocessed to convert string representations of lists into actual lists and to drop any rows with null values.

4. **Algorithms:**
    Each algorithm is implemented in separate functions and tested against the dataset to determine their accuracy and runtime.

5. **Results and Analysis:**
    The results of each algorithm are analyzed and compared to determine their effectiveness in solving the Knapsack Problem.

## Results

- **Generate and Test:** 100% accuracy but exponential runtime.
- **Greedy Algorithm:** 83.4% accuracy, runs in O(n log n) time.
- **Simulated Annealing:** Accuracy varies based on configuration, can achieve up to 100%.
- **Genetic Algorithm:** Accuracy varies based on configuration, can achieve up to 99.3%.

## Conclusion

Simulated Annealing with a cooling rate of at least 95% is recommended for achieving high accuracy and substantial speed when working with knapsacks.

## References

1. [Greedy Algorithm for 0-1 Knapsack: A Data Scientist’s Perspective](https://saturncloud.io/blog/greedy-algorithm-for-01-knapsack-a-data-scientists-perspective/)
2. [Simulated Annealing - Wikipedia](https://en.wikipedia.org/wiki/Simulated_annealing)
3. [Simulated Annealing Explained | Baeldung on Computer Science](https://www.baeldung.com/cs/simulated-annealing)
4. [Knapsack Problem Using Simulated Annealing Example](https://jamesmccaffrey.wordpress.com/2021/12/17/knapsack-problem-using-simulated-annealing-example/)
5. [Genetic Algorithm - Wikipedia](https://en.wikipedia.org/wiki/Genetic_algorithm)
6. [Applying a genetic algorithm to the traveling salesman problem](https://www.theprojectspot.com/tutorial-post/applying-a-genetic-algorithm-to-the-travelling-salesman-problem/5)
7. [Introduction to Hill Climbing | Artificial Intelligence](https://www.geeksforgeeks.org/introduction-hill-climbing-artificial-intelligence/)
