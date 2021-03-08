# krypton-01

Large part of the clerical work in this accountant organization consists of checking documents, classifying them and extracting some basic data from them.

This process today is basically manual, and therefore time consuming and prone to human error.

The idea behind this project was to create a code capable of based on the scanned PDF files  classify the documents into six types:

•	Invoices (Notas in Portuguese)
•	Personnel payments (RPA in Portuguese)
•	Receipts (Recibos in Portuguese)
•	Bank transfers (DOCs in Portuguese)
•	Bills (Boletos in Portuguese)
•	Others (Outros)

Note that the class others will encompass basically everything else not covered in the previous five.

Other important point is the fact that data will be extracted only from the three first classes. Here there is another difference the type of data extracted from each type has similarities but also differences:

Data and value will be extracted from all three types
Company number origin and destiny of the Invoice (Just the invoices)
Company paying number and social Insurance number of the person receiving (Just for Presonnel payments)


Document classification
Pyhton files to classify documents using NLP and extracting data through tesseract

