Chatbot for food orders online delivery using Dialogflow
===================
Build a chatbot for food orders online delivery using Google's Dialogflow ES. This bot supports two options,

1) New Order
2) Track Order

1) New Order: Sample Conversation

```
Bot: How can I help you? You can say things like (1) New Order (2) Track Order
User: New Order
Bot: What would you like to have? You can say things like 2 pizzas, one vada pav.
     Only order from this list: Vada Pav, Pav Bhaji, Mango Lassi, Pizza, Rava Dosa, Masala Dosa, Samosa
User: I would like to have 2 Rava Dosa and one plate of samosa
Bot: Added 2 Rava Dosa and 1 Samosa. Anything else?
User: Oh yes, add one mango lassi, please
Bot: Sure. Now we have 2 Rava Dosa, 1 Samosa and 1 Mango Lassi. Anything else?
User: Well, you know my cholesterol came high so let's remove Samosa
Bot: Sure. Now we have 2 Rava Dosa, and 1 Mango Lassi. Anything else?
User: Nope. That's it
Bot: Awesome. Your order is placed. Order id # 45. Your total bill is 19$ which you can pay at the time of delivery!
```

2) Track Order: Sample Conversation

```Bot: How can I help you? You can say things like (1) New Order (2) Track Order
User: Track Order
Bot: What is your order id?
User: 45
Bot: Order # 45, is in transit
User: How about 41
Bot: ORder # 41 is delivered
```


Directory structure
===================
backend: Contains Python FastAPI backend code
db: contains the dump of the database. you need to import this into your MySQL db by using MySQL workbench tool
dialogflow_assets: this has training phrases etc. for our intents
frontend: website code




