# insurer-performance-simulation
This project analyzes the financial performance of major insurance companies over multiple years and simulates competitive strategies using game theory. The analysis covers key insurance metrics such as underwriting profit, expense ratios, loss ratios, combined ratios, investment income, policies in force, and reserves for claims.

Beyond this, the project also explores "what if" scenarios for strategic changes in premiums and claims through analyzing payoff matrices using one of the most thought-provoking subjects that math has to offer: game theory. 

# Key Features
**1. Data Cleaning and Transformation**
- Most data aggregated through quarterly statements of each company
- Data not available on quarterly statements was estimated using probability functions
- Loaded multi sheet Excel financial data into Pandas
- Standardized metrics for comparison and visualization

**2. Financial Performance Analysis**
- Computed year-over-year changes for underwriting profit, ratios, investment income, policies, and reserves.
- Visualized trends with bar charts and heatmaps using Matplotlib and Seaborn.
- Highlighted significant changes and potential strategic implications.

**3. Strategic Modeling and Payoff Matrices**
- Created a payoff function to simulate the impact of premium and claim changes on underwriting profit.
- Generated normalized payoff matrices for company-vs-company comparisons across multiple financial metrics.
- Visualized matrices as heatmaps to identify strong and weak strategic positions.

**4. Game Theory & Nash Equilibria**
- Implemented an algorithm to detect Nash equilibria in payoff matrices.
- Identified stable strategies where neither company benefits by unilaterally changing premiums or claims.
- Provided actionable insights for strategic decision-making.

# Why You Should Care

**What is Game Theory**
- Game theory is a complex subject that aims to provide mathematical/logical solutions to perfect strategic decision making
- Much of game theory is derived from nash equilibria, which are solutions in which each player plays perfectly and improvement is impossible

**What is its use**
- For the purposes of this project, game theory helps us to comprehend the best action for each company, should an action occur from another company
- Finding Nash equilibria is essential to modeling optimal solutions in a case where perfect play can be assumed from the opposing company

# Project-Specific Results
- Through my analysis of Progressive specifically, I was able to find that Progressive, when competing with Geico, optimizes their payoff through high increases to their premiums
- This pattern holds across multiple financial metrics, including Premiums Earned, Estimated Number of Claims, and Policies in Force
- The data suggests overall that Progressive should adopt an assertive approach when competing with Geico, raising premiums in order to optimize their payoff

# Purpose of Calculating Payoffs
- Calculating payoffs can help you easily simulate scenarios of "If I do this, then what does {company} do?" and "If {company} does this, what is my best response"
- These scenarios can be simulated without actually taking on any financial risk

# How One Could Improve on this Project
- Currently, the analysis focuses on Progressive vs. Geico. Extending the payoff matrix simulations to all company pairs would provide a more complete view of the competitive landscape
- Additional improvements could include incorporating more sophisticated scenario modeling, such as varying multiple financial metrics simultaneously or adding stochastic elements like random claim events.

