# How to set up and run the NBA Database #
## Step 1: Install Python ##
Download and install the latest stable version of Python from the official [Python website](https://www.python.org/downloads/). Python 3.10 is required for this application to run. Make sure `pip` is included in the installation. It should be included but if not, you can download the latest stable release from <https://pip.pypa.io/en/stable/installation/>.
## Step 2: Install dependencies ##
Install the dependencies required for the application using `pip`. Navigate to the directory where the project code is located (`Host_Language`) in your terminal, and run the following command:
```
pip install -r requirements.txt
```
This command should install the packages required:
- pip==23.1
- setuptools==67.6.1
- wheel==0.40.0
- PyMySQL==1.0.3
- pandas==2.0.0
- nba_api==1.2
- bcrypt~=4.0.1
- matplotlib~=3.7.1
## Step 3: Import/Run SQL data dump ##
Import and run the `NBA_datadump.sql` file in your MySQL server to create the `nba_db` database.
## Step 4: Run the script ##
In the terminal, navigate to the directory `/Host_Language`, where the script is located, and run
```
python main.py
```
## Step 5: Provide database login credentials ##
The script will prompt you for a username and password. The username and password are the same as those used for the local running version of MySQL.
## Step 6: Ensure the script is using the correct database ##
The script uses the `nba_db` database, so make sure you have imported the data dump as described in [Step 3](#step-3-importrun-sql-data-dump "Goto step-3:-importrun-sql-data-dump").
- - - -
That's it! You should now have a working environment to run the ***NBA Database*** application.
