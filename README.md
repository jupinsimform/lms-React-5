# User list app - Functional specifications

## Practical-5

- Once the above app UI is created, let’s change static data to dynamic data using API implementation.
- Please go through the API documentation for getting the list of users on this page - https://reqres.in/
- Example: for listing 1st 6 users the endpoint for API is - https://reqres.in/api/users?page=1
- We also need to implement pagination in this application - so when the user clicks on page 2, the API endpoint should be https://reqres.in/api/users?page=2
- For Pagination I use custom API - https://servers-omega.vercel.app/users/p?limit=8&page=1
