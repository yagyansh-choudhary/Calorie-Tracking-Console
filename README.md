# Daily Calorie Tracker

## Description
The **Daily Calorie Tracker** is a simple Python-based command-line tool that helps users log and monitor their daily food intake by meal and calorie count. It provides a practical way to record each meal and automatically compute the total calories consumed in a day. This tool is useful for anyone aiming to manage their weight, understand dietary habits, or stay within a nutrition goal. The entire project is written in standard Python 3 (no external libraries).

## Features
- **Meal Logging:** Enter each meal and its calorie amount.
- **Calorie Summation:** Automatically calculate total calories.
- **Daily Limit Check:** Set a daily calorie goal and see if you exceed it.
- **Formatted Report:** Display meals, calories, total, and average neatly.
- **File Saving:** Save daily reports to `calorie_log.txt` with timestamps.

## Getting Started
To set up and run the project locally:

```bash
git clone https://github.com/username/daily-calorie-tracker.git
cd daily-calorie-tracker
python tracker.py
```

Ensure Python 3 is installed on your system.

## Usage Instructions
1. Run the script with `python tracker.py`.
2. Enter how many meals you want to log.
3. Enter each meal name and calorie amount.
4. Enter your daily calorie limit.
5. View your calorie summary table.
6. Optionally, save your session to a log file.

## Sample Output
```
Welcome to the Daily Calorie Tracker!
How many meals would you like to enter? 3
Enter the name of meal 1: Breakfast
Enter the calorie amount for 'Breakfast': 350
Enter the name of meal 2: Lunch
Enter the calorie amount for 'Lunch': 600
Enter the name of meal 3: Dinner
Enter the calorie amount for 'Dinner': 700

Meal Name           Calories
------------------------------
Breakfast           350.0
Lunch               600.0
Dinner              700.0
------------------------------
Total               1650.0
Average             550.00

Enter your daily calorie limit: 2000
You are within your daily calorie limit.
Would you like to save this session to a file? (yes/no) yes
Session saved to calorie_log.txt.
```

## File Structure
```
Daily-Calorie-Tracker/
├── tracker.py
├── calorie_log.txt
└── README.md
```

## Technologies Used
- Python 3.x (standard library only)

## Author Info
**Author:** Yagyansh Singh Ahlawat  
**Course:** Programming for Problem Solving using Python (ETCCPP102)

## Acknowledgments
- Python official documentation for input/output and file handling.
- Basic CLI examples referenced for formatting ideas.

## Academic Integrity Note
This project was completed individually and adheres to the academic integrity policy.
