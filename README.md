# pyDivideBigCSV
Divide a big CSV file into 2 or more files. / CSVファイルを2つ以上に分割する。

## Description.
<img src="https://github.com/okagen/pyDivideBigCSV/blob/master/Data/01.png" width="600">

## Usase.
  1. Specify the source CSV file to be divided. / 分割元のCSVファイルを指定する。
  ~~~
  csv_dir = ".\\Data\\"
  csv_name = "Sample.csv"
  ~~~
  
  2. Specify the number of file division. / ファイルの分割数を指定する。
  ~~~
  divCount = 3
  ~~~
 
  3. The divided CSV files are generated in the directory where the source CSV file is stored. The number of divisions and the number of first and last lines are added to the file name. / 分割元のCSVファイルが保存されているディレクトリに、分割されたCSVファイルが生成される。分割数と最初と最後の行の数がファイル名に付加される。
  <img src="https://github.com/okagen/pyDivideBigCSV/blob/master/Data/02.png" width="300">

  
