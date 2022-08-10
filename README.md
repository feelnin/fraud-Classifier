Project carried out during the Tera Data Science and Machine Learning bootcamp in the year 2022 The database that will be used for the development of this project contains approximately 6.3 million transactions. The data contained in this database is simulated and comprises 30 days. These transactions can be of different types and were executed via mobile devices. The features contained in this database are:

step - Step: represents the total hours elapsed since the beginning of the simulation. This feature will vary between 1 and 744 (30 days);

type - Type: type of transaction (deposit, withdrawal, debit, payment and transfer);

amount - Amount: total that was transacted;

nameOrig - CustomerOrigin: customer who initiated the transaction

oldbalanceOrg - OriginalBalanceOrigin: balance of the source account before the transaction;

newbalanceOrig - BalanceOrigin: balance of the origin account after the transaction;

nameDest -ClientDestino: destination client of the transaction;

oldbalanceDest -DestinationInitialBalance: balance of the destination account before the transaction;

newbalanceDest -SaldoFinalDestino: balance of the target account after the transaction;

isFraud - ÉFraud: flag that defines whether the transaction is fraudulent or not. In this simulation the purpose of the fraud is to take over the user's account, empty it by transferring it to another account and then withdrawing the money.

isFlaggedFraud - FlaggedAsFraud: automatically flagged by the bank as fraud for trying to transfer more than 200,000 in a single transaction.

Thus, the general objectives of the project were: exploratory analysis, modeling, feature engineering and evaluation of Random Forest and XGBoost models.
