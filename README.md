# esp32-api-connect-datatosdcard
This project uses a esp32 IDF code to connect to api as an html client and download the data to sd card, and search the data in sd card like student roll number with their ID tag number

The task of this project is given as below:

Task details:
Please find the API link:http://demo4657392.mockable.io/list-tag-ids
Following is the task:
1. When the system starts the latest data needs to be downloaded from the above API the data is
stored in persistent storage like SD card
2. In case the above API fails the system still uses the old stored persistent data. Please handle any
border cases
3. Task:
a. When anyone types a key from the above API e.g. "HYBpDQVhoCni2wuyCT" the console
replies with the value e.g. 56
b. Also print the query time for the above e.g. “Time for query: 50msec”
Note:
1. Take care of any border/failure cases when writing the code
2. Submission of code written on ESP32 with FreeRTOS will be preferred. But you can use any
micro-controller for the task (like Atmel, espressif(Preferred), STM, quectel, etc). The aim is to check
if you can write the code following the best practices and deliver it in time with quality.
3. Code only in C/C++(Python submissions will not be considered).
4. In case you are not able to do the above task within 2 days then to get back to us with whatever
