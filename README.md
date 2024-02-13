# etl-repo
In this project, it shows the process of extracting data from a json file, transform the column (USD) to (GBP), and then load it into a csv file. <br>
Two files are included in the repository other than the python file:<br>
  <b>-> bank_market_cap_1.json: It has the original data which has to be extracted for transforming<br>
  -> exchange_rates.csv: It has the exchange rates from USD to different corruncies.</b> <br><br>
 After running the code, it will make two files in the current directory (bank_market_cap_gbp.csv & log_file.txt)<br>
 <b>-> bank_market_cap_gbp.csv: It will have the required result in which the amount will be converted to GBP<br>
       -> log_file.txt: It will store all the logs as the ETL pipeline works in phases (Extract, Transform and Load)
