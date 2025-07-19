Brief Description How to Use ANN-Excel Software.

1. Paste data on "Data" tab.
1-1. First row is for the name of each column.
1-2. The last column should be dependent variable. Column 1 to (last - 1) for independent variables.
2. Count the number of data records (rows). That excludes the first row which is used for column names.
3. Click "Ctl-Sft-A" on "Data" tab. Then, you will see a new tab of "ANN" with scaled data between 0 to 1. Last line in ANN tab shows original maximum value of each column.
4. On "ANN" tab, click "Ctl-Sft-R". You can see the title of this software, then click ok.
5. You will see "number of training data?". Type the number of data records that were calculated in Step 2, then enter ok.
6. You will see "number of test data?". This step is optionally for testing/predicting additional records once ANN model is fully trained. Otherwise, just type 0, then enter ok.
7. You will see "number of input variables?". Type the number of independent variables, then enter ok.
8. You will see "maximum epoch?". Initially, try between 1,000 ~ 100,000.
8-1. If you type bigger number, you will get better result in terms of R^2 or RMSE. But, better result is not always good because it may cause "overfitting" issue.
9. In "Result" tab, you will see original dependent values in second column and ANN-calculated results in third column.
10. You can compare these observed and calculated values by plotting it using X-Y chart. Also, you can add R^2 value using Excel graph function (trend lines).
10-1. If you want to progress Step 10. automatically, Click "Ctl-G".

If you need any help, feel free to contact me (Zong Woo Geem; zwgeem@gmail.com).
