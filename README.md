# Crypto-Currency-Price
Function to get price of a cryptocurrency into a google drive sheet. Uses the [coinmarketcap api](https://coinmarketcap.com/api/)  
The Function takes in two parameters:  

The **cryptocurrency** that you want the price of  
The **currency** that you want the price of the cryptocurrency to be returned in

To use in google sheets:

1. Open script editor (Under tools)
2. File new "script file"- give it a name
3. Paste ccprice code and save
4. In your sheet, type in =ccprice(cryptocurrency, currency)  
   example:   
   =ccprice("ethereum", "USD") 

   
The currency parameter accepts the following currencies:  
"BTC", "USD", "AUD", "BRL", "CAD", "CHF", "CNY", "EUR", "GBP", "HKD", "IDR", "INR", "JPY", "KRW", "MXN", "RUB"   

If the cryptocurrency parameter isn't working, then find your cc on coinmarketcap and use the name in the website address. For example:

https://coinmarketcap.com/currencies/ethereum-classic/  
so you would type in =ccprice("ethereum-classic", "btc")

https://coinmarketcap.com/currencies/heat-ledger/  
so you would type in =ccprice("heat-ledger", "btc")
 
