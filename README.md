# Payment Wallet Application
- A payment application with CRUD operations and banking logical operations while maintaining the balance and account sections of the customers while providing the transactions.

- An developement of RESTful API for an Online Payment Wallet application. This API performs all the fundamental CRUD operations of any Online Wallet Banking platform with user validation at every step.

## Teach Stacks Implemented:
- Java
- Spring
- Spring Boot JPA
- Hibernate
- MySQL
- Swagger(UI)
- Lombok


## Problem Statement:-
- To create payment wallet application for XYZ bank. 
- Customers will be able to park their money in the wallet.
- Customer should be able to pay different bills using this wallet.
- They should be able to connect bank account with this payment wallet and add money. 
- Application should allow customers to check the balance, deposit money etc.

## Features(How to Work Application)
- User Login authrntication
- validation for the account number
- validation for the current user and user identification
- RESTful API with CURD operations
- Functional Front End For better user experience

# Modules:(Service Interface)
-	Account Module
-	Customer Module
-	Bill Payment Module
-	Transaction Module
-	Beneficiary Module
-	Bank Account Module

## Class Design:
Pojo Classes:
- Customer
- BeneficiaryDetails
- BackAccount
- BillPayment
- Transaction

# Application Desigen Method:--
- Entity Modules:
- DAO(Repository) Modules:
- Service Modules:
- Exceptions Modules:
- Controller:

# ------1.Entity Class Modules:------
- Login
- Coustomer
- Wallet
- BankAccount
- Transaction
- Transaction Type
- Bill Payment
- BeneficiaryDetails

# ------2. DAO(Repository) Modules------
- CoustomerDao
- CurrentUserSessionDao
- WalletDao
- BankAccountDao
- TransactionDao
- Bill PaymentDao
- BeneficiaryDetailsDao

# ------3. Service Modules(Class & Interface):-----
## interface 
- LoginService
- CoustomerService
- WalletService
- BankAccountService
- TransactionService
- Transaction Type Service
- Bill Payment Service
- BeneficiaryDetailsService

## Class Modules
- LoginServiceImpl
- CoustomerServiceImpl
- WalletServiceImpl
- BankAccountServiceImpl
- TransactionServiceImpl
- Transaction Type ServiceImpl
- Bill Payment ServiceImpl
- BeneficiaryDetailsServiceImpl

# -----4. Exceptions Modules:-----
- WalletNotFound
- CustomerException
- GlobalExceptionHandler
- BankAccountNotFound
-
-
-
-
-
-
-
-



# ------5.Controller Modules:------
- LoginController
- CoustomerController
- WalletController
- BankAccountController
- TransactionController
- Transaction Type Controller
- Bill Payment Controller
- BeneficiaryDetails Controller
 -----------------
# ER Diagram
The following Diagram depicts the flow of our Entity Relation Diagram to simplify the work flow.
![Swagger UI - Google Chrome 03-10-2022 09_20_51](https://github.com/nitish906/Payment-Wallet-Application/blob/main/PaymentApplication.jpeg)

# Roles And Responsibilities



# API Root Endpoint

 https://localhost:8888/
 
 https://localhost:8888/swagger-ui/#


# Screenshots(Back-end Application UI)

