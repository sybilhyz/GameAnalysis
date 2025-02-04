This repository contains materials and code for Aalto University's Game Analysis class, instructed by [Prof. Perttu Hämäläinen](http://perttu.info).

**Course contents:**

The course is a one week workshop, with approximately 8 hours per day:

* Day 1: Game analysis and research intro
* Day 2: Game design math, balancing, analytics. We will heavily utilize Colab notebooks (see below).
* Day 3: Psychology of game design: Behavioral game design, behavioral economics, monetization
* Day 4: Psychology of game design: Intrinsic motivation, emotion
* Day 5: Understanding the human body: Motor learning and performance for action game design, movement-based games. We usually conclude with a visit to [Valo Motion](https://valomotion.com) or Hoplop Pasila where Valo's climbing and trampoline games can be experienced.

**Approach:**

The course consists of lectures, exercises, and a [final assignment](lectures/final_assignment_instructions.pdf).  

Day 2 math and analytics exercises use [Google Colab](https://colab.research.google.com) and the Python notebooks in this repository. There are two notebooks that form a continuum with exercises of progressive difficulty. It is not expected that all students will complete all exercises. If one has zero programming experience, one might only work on the first notebook.

Click below to directly open the notebooks in Colab. After opening, select "copy to drive" to edit and run the code.

* [Intro: churn, virality, monetization](https://colab.research.google.com/github/PerttuHamalainen/GameAnalysis/blob/master/RetentionAndVirality.ipynb).

* [Advanced: Clash Royale balance analysis](https://colab.research.google.com/github/PerttuHamalainen/GameAnalysis/blob/master/ClashRoyaleBalance.ipynb). We look at card cost/benefit curves based on a Kaggle dataset of card stats.

Before starting with the Colab notebooks, you might also check the (simplified) Excel spreadsheet versions of the same:

* [spreadsheets/monetization_forecast.xlsx](spreadsheets/monetization_forecast.xlsx)
* [spreadsheets/Clash_Royale_cards_balance.xlsx](spreadsheets/Clash_Royale_cards_balance.xlsx)

Although game designers still often use spreadsheets, they are generally being replaced or at least augmented with notebooks, e.g., in game data science. The values in spreadsheet cells might be easier to tweak, but on the other hand, the Python code and equations are more human-readable, and Python enables more complex simulations.
