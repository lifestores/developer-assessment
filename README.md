# developer-assessment
A technical assessment exercise for Developer candidates

The purpose of this exercise is to assess your ability across several skills including;

- Time management and prioritisation
- Code organisation
- Familiarity with the core technologies
- Documentation

You are not necessarily required to complete the exercise but we encourage spending at least 4 hours to showcase as much as you can.

If you have any questions please email developers@lifestoreshealthcare.com

##Technologies

#### Frontend
- REACTJS
- Context API
- GRAPHQL

### Backend
- Django
- Graphene
- Docker

##### Test:
Given the Product data below: 

```
[
    {
        "name":"Paracetamol",
        "description":"Paracetamol (acetaminophen) is a pain reliever and a fever reducer",
        "sku":"8HE902",
        "price":300,
        "image":"https://www.m-medix.com/2759-large_default/emzor-paracetamol-tablets.jpg"
    },
    {
        "name":"Prednisolone",
        "description":"Prednisolone is a corticosteroid (cortisone-like medicine or steroid). It works on the immune system to help relieve swelling, redness, itching, and allergic reactions",
        "sku":"8HE809",
        "price":600,
        "image":"https://5.imimg.com/data5/RU/SX/JJ/SELLER-109604861/prednisolone-tablet-500x500.jpg"
    },
    {
        "name":"Lumefantrine",
        "description":"Lumefantrine is an antimalarial agent used to treat acute uncomplicated malaria.",
        "sku":"8HE809",
        "price":1200,
        "image":"https://i1.wp.com/nimedhealth.com.ng/wp-content/uploads/2020/09/IMG_20200920_082326-1.jpg?fit=2487%2C1599&ssl=1"
    },
    {
        "name":"Coflin",
        "description":"Coflin Is Used To Treat Coughs And Congestion Caused By The Common Cold, Bronchitis, And Other Breathing Illnesses.",
        "sku":"8HE809",
        "price":1200,
        "image":"https://www.m-medix.com/2677-large_default/dr-meyers-coflin-expectorant-100ml.jpg"
    }
]
```

Using Python, Graphene, Docker, etc.
a) Create a Product model
b) Create a command to migrate the products data above into the database
c) Create a GraphQL endpoint to return all the products to the FE
d) Encapsulate your back-end services in docker containers

Using React, Context API, and GraphQL
a) Create a products page to show the GraphQL fetched products in cards with appropriate product data(name, price, pictures, etc.)
b) Each product should have an "Add to cart" button
c) On click add to cart, show cart summary component as an overlay and add the product to the cart.
d) Allow increment(+), decrement(-) and delete functionality on each cart item in the cart

Once complete share instructions on how we can review the code and run
the application.

#### EVALUATION CRITERIA
Your solution will be evaluated for:
1. Design/Architecture Quality
2. Code Quality
3. User Experience (Frontend)
4. DB Migration
5. Tests
