# TallyNaturalLanguage


This concept was built using [Natural Language in Tally ](https://help.tallysolutions.com/article/te9rel55/SMS/Natural_Language.htm?)



## The following Prompts will work in the demo


### 1. Ledger Creation 

**```Without mentioning Group Name```**

 - Create Ledger Kavilan
 - Create Ledger ICAI


**```With Group Name```**

Create Ledger Kavilan SundryDebtors

***```With Opening Balance```**

Create Ledger server02 fixedassets -15000
Create Ledger icai sundrycreditors 15000


### Transaction creation

Make Payment 3000 to ICAI

### Stock Creation

Create Item DustCovers FinishedGoods Nos 10 550

### Sales Order
Create SO <PartyName> <Order Reference No> <ItemName 1> <Qty 1> <Amount 1> <ItemName 2> <Qty 2> <Amt 2> ...... <ItemName n> <Qty n> <Amt n>

Create SO Kavilan PO1101 MotherBoard 15nos 10000

Create SO Kavilan PO1102 AssembledPIV 10 25000 MotherBoard 15nos 10000 DustCovers 8 500
