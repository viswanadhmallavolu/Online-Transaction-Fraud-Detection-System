# Behavior and Location-Based Risk Analysis for Secure E-Commerce Payments
 
* This project implements a Behavior and Location-Based Risk Analysis module for detecting suspicious payment activity in online transactions. The system analyzes historical    transaction data to identify abnormal spending patterns and verifies the user’s location using an IP geolocation service before allowing payment execution.
* The fraud detection logic acts as a pre-payment validation layer, ensuring that suspicious transactions are flagged before the payment gateway processes the transaction.
* For location analysis, we utilised [ipinfo.io](https://ipinfo.io/). To obtain the location, we must utilise the ipinfo.io access token. 

### How to Use?
    git clone https://github.com/viswanadhmallavolu/Online-Transaction-Fraud-Detection-System    
    cd credit-card-fraud-detection.git
    pip install virtualenv
    virtualenv env
    .\env\Scripts\activate
    pip install -r .\requirements.txt
    After working
    deactivate
