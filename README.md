# stopwatch

# Period Tracker Script
This Python script helps users track menstrual cycle dates and predicts the next period date based on the average cycle length calculated from previous dates. The script is interactive, prompting the user to enter their most recent period dates, then providing an estimated date for their next cycle.

# Features
Cycle Length Calculation: Computes the average length of the user's menstrual cycle based on the dates provided.
Next Period Prediction: Predicts the next period date by adding the average cycle length to the most recent period date.

# Getting Started
1. Prerequisites
Ensure you have Python 3 installed on your machine.

2. Running the Script
To run the script, save it as period_tracker.py and execute it with the following command:
python period_tracker.py

Example Usage
1. Input Period Dates: When prompted, enter your recent period dates in YYYY-MM-DD format.
2. View Prediction: The script will calculate your average cycle length and predict your next period date based on this average.

# Code Overview
1. calculate_cycle_length: Computes the average cycle length based on consecutive period dates.

2. predict_next_period: Uses the average cycle length to estimate the next period date.

3. get_dates: Prompts the user to input previous period dates.

4. main: Runs the main program, gathers user input, and displays the prediction.

# Potential Enhancements
Error Handling: Add checks for invalid dates and out-of-order entries.
Calendar Integration: Export predictions to a calendar format.
Longer Tracking: Store dates for future predictions and accuracy over time.
