## CO2 Dashboard
# This dashboard provides a visualization of CO2 Emissions by year, country, and GDP
Project setup:

First, create a venv running this commands:
1. python3 -m venv ./
2. source bin/activate
3. pip3 install hvplot jupyterlab
Then we need to deactivate our venv, otherwise we will get some displaying bugs
4. deactivate
5. pip3 install panel
6. source bin/activate
To launch the web dashboard run this command
panel serve dashboard.ipynb
