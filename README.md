# AI in Trading NanoDegree (AITND)
This repository contains code for Udacity's [AI in Trading NanoDegree](https://www.udacity.com/course/nd880).
## Repository File Structure
    .
    ├── project/             # Code for projects in the classroom
    ├── quiz/                # Code for quizzes in the classroom
    ├── helper.py            # A helper file shared across projects and quizzes
    ├── requierments.txt     # Common packages used for projects and quizzes
    └── tests.py             # Common test functions for unit testing student code in projects and quizzes
    
## Projects

### Trading with Momentum
In this project, I have implement a trading strategy on my own, and tested to see if it has the potential to do a profitable trading. I have supplied with a universe of stocks and time range. provided with a textual description of how to generate a trading signal based on a momentum indicator. Computed the signal for the time range given and applied it to the dataset to produce projected returns. Finally, Perfomed statistical test on the mean of the returns to conclude if there is alpha in the signal. 

#### Result

With the Alpha analysis, the observed p-value is 0.073359, which is higher than the given threshold of 0.05 and we cannot reject the null hypothesis, the actual population mean return from the signal is zero.

*Conclusion*: Our null hypothesis is correct and the signal might not always return positive results.
**
