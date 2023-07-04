# Product Manager RESTful API
This documentation describes a RESTful API that allows basic product management.
The API offers CRUD (Create, Read, Update, Delete) operations for manipulating product data.

## Resources
The API offers the following features:

/products: Represents the collection of available products.
/products/{id}: Represents a specific product identified by its ID.

## Operations
The API supports the following operations:

List products: GET /products

Returns a list of all available products.
Get a specific product: GET /products/{id}

Returns details for a specific product based on the given ID.
Create a new product: POST /products

Creates a new product based on the data provided in the request body.
Update an existing product: PUT /products/{id}

Updates data for an existing product based on the provided ID and the data provided in the request body.
Delete a product: DELETE /products/{id}

Excludes a specific product based on the given ID.

## Parameters
The following parameters can be used in requests:

{id}: The unique ID of a product, used to identify a specific product.
Request and response body
Product data is provided in the body of POST and PUT requests, using a JSON format. The response body will be returned in JSON format and will contain details of the requested product.

## Status codes
The API uses the following HTTP status codes:

200 OK: The request was successful.
201 Created: The product was successfully created.
204 No Content: The request was successful, but there is no content to return.
400 Bad Request: The request has invalid parameters or incorrect data.
404 Not Found: The requested resource was not found.
500 Internal Server Error: A server error has occurred.
Authentication
The API does not require authentication to access product features.

## Complete documentation
[Documentation](https://documenter.getpostman.com/view/21882176/2s93zE2zPT)

## Conclusion
This RESTful API allows for basic product management, allowing you to create, read, update, and delete products. Use the endpoints and operations described in this documentation to interact with the API and efficiently manage your products.
