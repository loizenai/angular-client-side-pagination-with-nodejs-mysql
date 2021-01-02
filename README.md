# Angular Client Side Pagination with Nodejs + MySQL

https://loizenai.com/angular-client-side-pagination-with-nodejs-mysql/

![Angular Client Side Pagination with Nodejs + MySQL](https://loizenai.com/wp-content/uploads/2020/12/Angular-Client-Pagination-Nodejs-MySQL-Example.png)

Tutorial: ” Angular Client Side Pagination with Nodejs + MySQL – Server Side Pagination in Node.js Angular MySQL database + Express + Sequelize CRUD ”

In the tutorial, I introduce how to build an “Angular 10 Nodejs Pagination RestAPIs Example with MySQL database (Server Side Pagination with filtering and sorting)” project using Express framework and Sequelize crud queries to interact with database’s records.

– Nodejs Express project (server side pagination) produces pagination RestAPIs with MySQL database records using Sequelize CRUD queries.
– Angular 10 project (client side pagination) will consume the Node.js pagination RestAPIs then show up on component’s views.

## Architecture – Angular Client Side Pagination with Nodejs + MySQL

![Architecture – Angular Client Side Pagination with Nodejs + MySQL](https://loizenai.com/wp-content/uploads/2020/08/Angular-Nodejs-MySQL-RestAPIs-Overview.png)

In the tutorial “Server Side Pagination in Node.js Angular 10”, We develop 2 projects:

- Backend Project – Nodejs MySQL Pagination Application gets data from MySQL database then provides RestAPIs with pagination, filtering and sorting function for frontend
- Frontend Project – Angular Application use HttpClient to fetch data from Backend Application then shows them in Bootstrap table with pagination, filtering and sorting functions

## Project Goal – Angular Client Side Pagination with Nodejs + MySQL

– Make a request at API: /api/customers/pagefiltersort with pagination, filtering and sorting params as below:

page: 0 – first page
size: 5 – size of a page
salary: 4000 – filtering by salary field
agesorting: true – sorting by age
desc: true – descending or ascending sorting
– Result:

![Nodejs MySQL Pagination RestAPIs Examples](https://loizenai.com/wp-content/uploads/2020/08/Nodejs-MySQL-Pagination-RestAPIs-Examples.png)

– Angular Frontend Pagination with Filtering and Sorting table:

![– Angular Frontend Pagination with Filtering and Sorting table](https://loizenai.com/wp-content/uploads/2020/08/Angular-Pagination-Frontend.png)

## Video Guide – Angular Client Side Pagination with Nodejs + MySQL

For the tutorial “Angular Client Side Pagination with Nodejs + MySQL”, I create a Youtube video guide with clearly steps to debug full-stack for all running flows of living code from Angular client to Nodejs backend pagination:

https://youtu.be/pkQY56B5Ut0

## Overall Server Side Pagination in Node.js/Express Sequelize MySQL Pagination

To handling Pagination RestAPI requests and do Paging Filtering and Sorting queries with MySQL database, we create a backend web Node.js application with 4 main points:

![Nodejs Pagination Overall Architecture](https://loizenai.com/wp-content/uploads/2020/08/Nodejs-Pagination-Overall-Architecture.png)

- To handle pagination RestAPI requests with Node.js, We use Express framework.
- To do pagination filtering and sorting queries with MySQL database, We use Sequelize ORM.
- We define all RestAPI URLs in router.js.
- We implement code how to process each paging filtering and sorting RestAPI request in controller.js file.

## Nodejs/Express Sequelize Pagination Queries

To do the pagination with database, Sequelize ORM provides 2 model methods for supporting the purpose with limit and offset parameters:

.findAll() – Search for multiple elements in the database
.findAndCountAll() - Search for multiple elements in the database, returns both data and total count
How about limit & offset for nodejs pagination?

limit is the maximum number of records to fetch
offset is the quantity of records to skip
For example, if we have total 12 items:

{ offset: 5 }: skip first 5 items, fetch 7 remaining items.
{ limit: 5 }: fetch first 5 items.
{ offset: 5, limit: 5 }: skip first 5 items, fetch 6th and 10th items.


## Tutorial Link

https://loizenai.com/angular-client-side-pagination-with-nodejs-mysql/

## Related post

- [Angular 10 Spring Boot JWT Authentication Example – Angular 6, 8, 9, 10 + Spring Security + MySQL/PostgreSQL](https://loizenai.com/angular-spring-boot-jwt-authentication-example-angular-6-8-9-spring-security-mysql-postgresql/)
- [Angular & Nodejs JWT Authentication fullstack Example | Angular 6, 7, 8, 9 – Express RestAPIs + JWT + BCryptjs + Sequelize + MySQL/PostgreSQL](https://loizenai.com/angular-nodejs-jwt-authentication-examples-tutorials/)
- [Django RestAPIs Tutorial – Build Post/Get/Put/Delete request Examples to MySQL/PostgreSQL databases](https://loizenai.com/angular-nodejs-jwt-authentication-examples-tutorials/)
- [Server Side Pagination in Node.js Angular 10 + MySQL + Sequelize](https://loizenai.com/angular-nodejs-jwt-authentication-examples-tutorials/)
- [Spring Boot Angular Pagination Example](https://loizenai.com/angular-nodejs-jwt-authentication-examples-tutorials/)
- [Spring Boot Angular 11 Pagination Example](https://loizenai.com/angular-nodejs-jwt-authentication-examples-tutorials/)
- [Angular Table Pagination Filtering Sorting with SpringBoot RestAPIs + Bootstrap Example – Angular 10-9-8-6 Tutorial](https://loizenai.com/angular-nodejs-jwt-authentication-examples-tutorials/)
- [Angular 10 Server Side Pagination in Nodejs MongoDB Example](https://loizenai.com/angular-10-nodejs-mongodb-pagination-example/)

## Youtube Video

- https://www.youtube.com/watch?v=dTR-41_jMvc&t=46s
- https://www.youtube.com/watch?v=lb5LVzJbquI&t=476s
- https://www.youtube.com/watch?v=DoV8xfA8WBo&t=30s
- https://www.youtube.com/watch?v=rYmf_MthobU&t=376s
- https://www.youtube.com/watch?v=7ZfInOvFsz0&t=1308s
