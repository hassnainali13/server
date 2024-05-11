**RESTful API Quick Guide**
**What is this API?**
This API helps you interact with our service programmatically. You can perform various actions like retrieving data, updating information, and more.
**1. POST Request**
Description: Adds new data to the server.
Example Request:
POST localhost:5000/addProducts
**json code:**
    {
"name": "product name",
"description": "description",
"price": Amount ,
"category": "category"
}
**Postman to Data Insert with Response ScreenShort Picture**
![image](https://github.com/hassnainali13/server/assets/95144055/19695df3-ca83-409f-9543-4a72cbede3b8)

**2. GET Request**
Description: Retrieves data from the server.
Example Request:
GET localhost:5000/readAllProducts

Example Response:
**Postman to Data Read ScreenShort Picture**
![image](https://github.com/hassnainali13/server/assets/95144055/16208a17-ecff-44f9-aae1-e86338e06975)

**3. UPDATE Request By ID**
Description: Updates existing data on the server.change data if you want
Example Request:
PUT localhost:5000/localhost:5000/update/(Enter id)

**json code:**
    {
"name": "product name",
"description": "description",
"price": Amount ,
"category": "category"
}

Example Response:
**Postman to Data Update ScreenShort Picture**
![image](https://github.com/hassnainali13/server/assets/95144055/29a0bec1-3c57-48ea-ae22-f3982f9fc446)


**4. DELETE Request**
Description: Deletes existing data from the server.
Example Request:
DELETE localhost:5000/delete/(Enter id)

Example Response:
**Postman to Data Delete ScreenShort Picture**
![image](https://github.com/hassnainali13/server/assets/95144055/11e33746-cec2-4875-9764-c4d2ff081bf9)

**Error Handling**
We follow standard HTTP status codes to indicate the success or failure of a request. Detailed error messages are provided in JSON format.
