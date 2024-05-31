# E-Commerce-Site-Back-End
    
![License](https://img.shields.io/static/v1?label=license&message=MIT&color=yellowgreen) 
    
An E-Commerce Site Back End that utilizes a REST API to store information about the products, product categories, and product tags sold on the site.
    
## Table of Contents
    
* [Installation](#Installation)
    
* [Usage](#Usage)
    
* [Tests](#Tests)
    
* [License](#License)
    
* [Author](#Author)
    
## Installation
    
In order to install this API, use the attached [link](https://github.com/raulds-fmtx/E-Commerce-Site-Back-End.git) to clone the git repository to your local system. Then run the command `npm install`. In an integrated terminal to install the required dependencies to your system. Next, in the project directory created a `.env` file that contains the following text:

`DB_NAME='ecommerce_db'`\
`DB_USER='your_user'`\
`DB_PASSWORD='your_password'`
    
## Usage

To run this program, run the following command in an integrated terminal to create a new `ecommerce_db`.

`psql -U your_user`

Enter your postgres password when prompeted, and then run the command:

`\i ./db/schema.sql`

To optionally seed your database, run the following command:

`npm run seed`

To intialize your local systems connection to your newly created database, run the following command:

`npm start`

API calls may then be made using the following format:

`localhost:3001/api/path_parameters`
    
[Click Here to View a Demo.](https://drive.google.com/file/d/1BIFdW1BHbT66Eh11Ar-dI0pXwXgU6UhY/view?usp=sharing)

## License
    
This project is license under the MIT License - see the [License](https://choosealicense.com/licenses/mit/)
    
## Author
    
Raul Santos
    
Github: [raulds-fmtx](https://github.com/raulds-fmtx)

Repo: [E-Commerce-Site-Back-End](https://github.com/raulds-fmtx/E-Commerce-Site-Back-End)