 [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
# alisters-ecommerce-back-end

## Description
Internet retail, also known as e-commerce, is the largest sector of the electronics industry, having generated an estimated US$29 trillion in 2017 (Source: United Nations Conference on Trade and Development). E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to the prevalence of these platforms, I should understand the fundamental architecture of e-commerce sites.

This challenge is to build the back end for an e-commerce site. I’ll take a working Express.js API and configure it to use Sequelize to interact with a MySQL database.

### User Story
```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```
### Acceptance Criteria
```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
```
## Demo Link
https://drive.google.com/file/d/1JIQjPco8r6ZBcsMKLLKmbUkjQfUfPX49/view

## Link to Repo
https://github.com/porteous89/alisters-ecommerce-back-end


## Screen Shots

Starting mysql and sourcing Database

<img src="assets\using-mysql.png" width= 45% >

Seeding Database

<img src="assets\seeding-databases.png" width= 45% >

## Built Using
- Node.js
- Express.js
- Dotenv
- mysql2
- sequelize
- Insomnia

## Usage
- Routes can be manipulated through Insomnia.
For each Table: Product, Tag & Category
  - Get All
  - Get 1 by ID
  - Post to Create new
  - Put to update
  - Delete by ID

## License
This project is licensed under the MIT license. See the [LICENSE](https://opensource.org/licenses/MIT) file for details.
 [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Credits
Learn Sequelize
https://www.youtube.com/watch?v=pxo7L5nd1gA

Insomnia
https://docs.insomnia.rest/insomnia/send-your-first-request

Dotenv Intro
https://medium.com/chingu/an-introduction-to-environment-variables-and-how-to-use-them-f602f66d15fa

## contribution
PLease checkout my github link for contributions -  [https://github.com/porteous89](https://github.com/porteous89).

## Questions
If you have any questions about the repo, open an issue or contact me directly at alisterporteous@hotmail.com. You can find more of my work at [https://github.com/porteous89](https://github.com/porteous89).
