# SentimentAnalysis-using-NLTK-with-Python
This program predicts the reviews provided by users as positive or negative. The reviews are stored in txt files positive1.txt and negative1.txt.
One problem that can be faced while running the program is that the .txt files may show unknown type. To resolve this open your terminal and check if the file is showing unknown type by running the command : file -i positive1.txt
If it shows charset=unknown then type the following command to convert the file to ascii type which is a subset of utf-8 encoding.
cat -v originalfilename.txt > newfilename.txt
The file will then be converted to ascii so while file handling, no problem will be faced regarding the encoding.
