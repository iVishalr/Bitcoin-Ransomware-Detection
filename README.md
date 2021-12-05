# Bitcoin Ransomware Detection using deep neural networks

Bitcoin Ransomware Detection is a project for the course Data Analytics UE19CS312, PES University.

Team Members

1. Abhishek Aditya BS - PES1UG19CS019
2. Vinay P Naidu - PES1UG19CS567
3. Vishal R - PES1UG19CS571

## Report Links
Literature Survey [Report](https://drive.google.com/file/d/11vb0aNbmLAiJf4WmARSgy5_DmnAvYWKn/view?usp=sharing)

Final Report [Report](https://github.com/iVishalr/Bitcoin-Ransomware-Detection/blob/main/Bitcoin-Ransomware-Detection.pdf)

## Dataset Description

Dataset from the UCI BitcoinHeistRansomwareAddressDataset Data Set available at [link](http://archive.ics.uci.edu/ml/datasets/BitcoinHeistRansomwareAddressDataset)

Number of instances: 2916697

Number of attributes: 10

Attribute Information

Features :

`address` : String. Bitcoin address.

`year` : Integer. Year.

`day` : Integer. Day of the year. 1 is the first day, 365 is the last day.

`length` : Integer.Length is designed to quantify mixing rounds on Bitcoin, where transactions receive and distribute similar amounts of coins in multiple rounds with newly created addresses to hide the coin origin.

`weight` : Float. Weight quantifies the merge behavior (i.e., the transaction has more input addresses than output addresses), where coins in multiple addresses are each passed through a succession of merging transactions and accumulated in a final address.

`count` : Integer. Similar to weight, the count feature is designed to quantify the merging pattern. However, the count feature represents information on the number of transactions, whereas the weight feature represents information on the amount (what percent of these transactions is output) of transactions.

`looped` : Integer. Loop is intended to count how many transaction i) split their coins; ii) move these coins in the network by using different paths and finally, and iii) merge them in a single address. 

`neighbors` : Integer. (Not explained in dataset, but assumed to be number of network neighbors involved in the transaction) 

`income` : Integer. Satoshi amount (1 bitcoin = 100 million satoshis).

`label` : Category String. Name of the ransomware family (e.g., Cryptxxx, cryptolocker etc) or white (i.e., not known to be ransomware).
