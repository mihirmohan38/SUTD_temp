# **Automatic health declaration script for SUTD**

This is an automated python script using selenium to automatically fill in the compulsory health declaration by SUTD.

## Dependencies

1. Chrome webdriver: https://chromedriver.chromium.org/downloads (please download according to your current chrome version)

2. Pip install the required module in the script : Selenium 

3. (Only required if you use version 1.0) Set up environment variable:

   - userid --> your SUTD user id (e.g 100xxxx)

   - pw     --> your SUTD password

     **(!) And remember to update it whenever you change your sutd password**

## Usage

1. Make sure the script itself can run manually first 

   - Open python IDE and run the script manually. 
##   - Open the script and edit the path for the webdriver
   - There are 2 versions, version 1.0 requires environment variable to login where as version 1.1 fetch the password and userid from chrome. Version 1.0 should be easier to run since it grab id and pw from environment variable whereas version 1.1 is more convenient but only tested on linux.

2. Automate it

   a. For Window:
   https://towardsdatascience.com/automate-your-python-scripts-with-task-scheduler-661d0a40b279

   - You can use the .bat file in the executable_file folder as the execution program, remember to edit the path to your python environment and python file respectively in your .bat file.
   - Use Window Task scheduler to run the bat file at the scheduled time
   - Warning version 1.1 has not tested for window, recommend to use 1.0



