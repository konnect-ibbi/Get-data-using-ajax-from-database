# Get-data-using-ajax-from-database

## About The Project
This is small project of PHP MYSQLI and AJAX

# How It Work
  This file ---- sql-ajax-custumer-search.php ---- Containing form to take Input form the user.
  
  And contianing Script File of ajax which take input on keyup event.
  
  And send it to server to process server file ---- search.php ----
  
  This File ----- Search.php ------ Recieve parameter from ajax File of input taken by user.
  
  The input check 
  - if input is empty in response give empty.
  
  - If input is something and match extract and show output from the database in table form through mysqli machting first name first letters of person
  
  - if input is not found show That No record found 
  
  # Instructions
  
  
  # Download 
  - sql-ajax-customer-search.php
  - search.php
  - sql-file.sql
  - extract to your xamp folder
  # Next 
  - Create database name it logindata in your phpmyadmin
  - Import the --- sql-file.sql --- in there
  - Now access the form file which is sql-ajax-customer-search.php
