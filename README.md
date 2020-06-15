# NFL Arrest 
This project aims to analyze the number of arrests that took place during home game.

## Introduction

NFL Game Day Arrest: NFL is very popular sports in USA. The game day holds special place for fans. However, there are also lots of arrest happening during game day.  This dataset consists of public records requests made by the Washington Post to police departments that oversee security at each NFL stadium. The main dataset includes fields such as the day of the week, which teams were playing on which home field, and the score of the game, between 2011 and 2015. . Sometime fans take it to next level and start fighting and get in trouble when their team underperform. Everyone one wants to enjoy the game but at times you hear about the brawl, stabbing and shooting happening during NFL games.
Interest: 	
Are the arrest likely to increase if home team lost the game?
Does the number of arrest increase during divisional games when the teams see each other twice a year every season?
Does the number of arrest increase as the season progress?
Challenges:
Not all the teams reported data for analysis.
Each team play divisional opponents twice other than that no guarantees team play against each other.
No proof that arrests are entirely game related.




### Getting Started

List are the packages that need to be installed:
import pandas as pd
import seaborn as sns
import numpy as np
import matplotlib.pyplot as plt
from statsmodels.tsa.arima_model import ARIMA
import sklearn

