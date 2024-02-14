# Solve Sudoku with AI
> Harnessing AI to crack the complexities of Sudoku, including diagonal variations.

This project represents a sophisticated AI-based approach to solving Sudoku puzzles, employing a constraint satisfaction strategy. By extending the solution to tackle diagonal Sudoku puzzles, it showcases an innovative application of AI techniques to enhance traditional problem-solving methods.

![Solve Sudoku with AI](./sudoku_visual.gif)

### Project Overview
Developed an AI agent capable of solving standard and diagonal Sudoku puzzles. This involves applying advanced algorithms to navigate the intricate constraints of Sudoku, ensuring that each row, column, and principal diagonal adheres to the rule of containing all digits from 1 to 9 without repetition.

### Key Features
- **Constraint Satisfaction**: Utilizes a robust constraint satisfaction framework to efficiently solve Sudoku puzzles, demonstrating the power of AI in logical problem solving.
- **Diagonal Sudoku Solver**: Expands the challenge by solving diagonal Sudoku puzzles, adding a layer of complexity to test the AI's capabilities further.

### Implementation Details
The core of this solution is encapsulated in `solutions.py`, where the AI agent's logic and strategies are meticulously crafted. This file contains the algorithms that embody the essence of constraint satisfaction applied to Sudoku solving.

### Getting Started
To explore the AI agent and attempt solving Sudoku puzzles on your own:

1. **Clone the repository**:
   ```
   git clone https://github.com/yourusername/AI-Sudoku-Solver.git
   ```

2. **Navigate to the project directory** and run the solver:
   ```
   cd AI-Sudoku-Solver
   python solutions.py
   ```

### Future Enhancements
- **Optimization**: Continuous efforts to optimize the algorithm for speed and efficiency, allowing for real-time solving of even the most complex puzzles.
- **AI Techniques Expansion**: Exploring the incorporation of other AI and machine learning techniques to further enhance the solving strategy, potentially introducing predictive analytics for preemptive move planning.
- **User Interface Development**: Developing a user-friendly interface that allows users to input puzzles interactively and visualize the solving process in real time.
