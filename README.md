Setting up the code base

1. Clone the repository

git clone https://github.com/renu-matlib/Team18_Matlib_marvels_PythonHackathon_Apr24.git

2. Move to the below directory
cd Team18_Matlib_marvels_PythonHackathon_Apr24

3. Create your branch
git branch branch_name

4. checkout your branch: this command moves to your branch
git checkout branch_name

OR 
Creates the branch and moves inside it (skipping step 3 and step 4)
git checkout -b branch_name

Moves to main branch
git checkout main 

# Syntax to be used in the code:

import pandas as pd
import numpy as np
import matlibplot.plot as plt

Variable name should be a valid column name. you can keep it short like abbreviation.
any temporary variable as temp_<variable_name>
integer variable i_<first letter should be capital>
similarly for other datatypes

array variable arr_<first letter should be capital>

dataframe as df_<first letter should be capital>


Always add a valid commit message while committing the code.
After pushing the code it shuld be reviewed. whoever is reviewing the code, can add their comments and send a message. If valid you can change and send to review again. Only after reviewing, the reviewing person can checkin the code

when starting the code, please add comments in the beginning, on the <your name> <question number> : <question> it can be double line comment also. So everytime we merge we can verify all your answers are there. also it wil be easy for the reviewers to check the answers.

Add more comments wherever needed. 

Each of us will concentrate on 5 additional analysis maximum, while doing the questions itself. 

To avaoid last merge conflicts at the end, We will checkin the code daily and merge it to main branch. and pull the data every morning and work on top of it. 

Challenges:
If you find any challange, write down in a file and push it in the main branch, We will use it for presentation. Syntax as <your name>_Challenge

Code Reviews Principles:
Functionality, Labels, Charts, Syntax, Units, Screenshots, etc.
Missing Inline Comments, Spelling mistakes can also be a review point.


