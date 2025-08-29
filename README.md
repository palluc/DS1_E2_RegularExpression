<!---
Decision Science 1 Class - Exercise 2
# DS1_E2_RegularExpression
--->
## Regular Expression and Pandas Dataframe

#### Objective
The purpose of this program is to use regular expression on data files for the purpose validating data (phone number and email address) before saving to a file. The good data records are written to separate file than that of the erroneous records (the ones that do not pass validation).

The data records are then read into a pandas dataframe for data processing and sorting.

#### Tools Used
Required tools to run the program are :</br>
\- Jupyter Notebook (It is recommended to install full Python distribution with Anaconda Python distribtion) </br>
\- a csv file having columns\: first_name,last_name,company_name,address,city,province,postal,phone1,email,web,exam_1,exam_2,exam_3

#### Program walk-through

- Launch the Jupyter Notebook: <br/>
<p style="border: 2px solid #000000; padding: 1px;">
<table><tr><td>
<img src="https://github.com/user-attachments/assets/a58cc02a-3947-4d2b-ad60-7ea704e391ae" width="80%" height="50%" alt="Launch the Jupyter Notebook" />
</td></tr></table>
</p>
</br>

- Define regular expression for the phone column having format : ddd-ddd-dddd (where d is a digit)<br/>
- Define regular expression for the email column having format : xxxxxxx@xxxxx.xxx (where x is an alphanumeric character)<br/>
<p style="border: 2px solid #000000; padding: 1px;">
<table><tr><td>
<img src="https://github.com/user-attachments/assets/5a477d03-3ec0-4436-9726-8dac1b5f1b88" width="80%" height="50%" alt="Identify data errors" />
</td></tr></table>
</p>
</br>

- Verify that the phone column and the email column are in the correct format<br/>
<p style="border: 2px solid #000000; padding: 1px;">
<table><tr><td>
<img src="https://github.com/user-attachments/assets/6b872c2d-f070-4110-a7c9-4bc8ebda7a35" width="80%" height="50%" alt="Identify data errors" />
</td></tr></table>
</p>
</br>

- Read in file with validated data into pandas dataframe \: <br/>
<p style="border: 2px solid #000000; padding: 1px;">
<table><tr><td>
<img src="https://github.com/user-attachments/assets/de502314-5a3d-4654-bd28-6c04faf4de9f" width="80%" height="50%" alt="collects 3 sets of data from the console" />
</td></tr></table>
</p>
</br>

- Perform data processing on the pandas DF \:  <br/>
<table><tr><td>
<img src="https://github.com/user-attachments/assets/342edf6a-0909-4776-90a6-ea11ec97d946" height="80%" width="50%" alt="Output FIles" style="border: 2px solid black;"/> 
</td></tr></table>
</br>
