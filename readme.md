<h1>Income Expense Manager with Laravel</h1>

This project is forked from [nayeemdev/incomeExpense](https://github.com/nayeemdev/incomeExpense). I did this project in order to learn the _Laravel Framework_. It's a simple application that I use to track my own income and expense.

## About Income Expense Manager

Income Expense Manager is an open source web application made with Laravel.Features of this software:

- Add, Edit, Delete Daily income,expense or any Note.
- In the Dashboard you can see This month Cost with how many income, expense and balance also.
- It has a calculator made with JS.You can calculate with this.
- And also you can see all your summary like all income and expense from all time that you added in this software.

Income Expense Manager is open source and if you want you can contribute.

## Screenshot

![Screenshot (7)](https://user-images.githubusercontent.com/40033062/66742324-364e0300-ee99-11e9-98c3-2ab492bd154d.png)

![Screenshot (8)](https://user-images.githubusercontent.com/40033062/66742412-64334780-ee99-11e9-99dc-6031ebb16cad.png)

![Screenshot (9)](https://user-images.githubusercontent.com/40033062/66742420-69909200-ee99-11e9-8fa5-ce8c95007823.png)

![Screenshot (10)](https://user-images.githubusercontent.com/40033062/66742428-6d241900-ee99-11e9-9089-e1bd2e2311ad.png)

## Installation Process

Clone this repository-
```sh
git clone https://github.com/nayeemdev/incomeExpense.git
```
Goto incomeExpense Folde
```sh
cd incomeExpense
```
Copy .env.example to .env 
```sh
cp .env.example .env
```
Install composer for vendor file
```sh
composer install
```
Create a database and set information to .env


Run migrate (--seed for faker data)
```sh
php artisan migrate --seed
```
Then run 
```sh
php artisan serve
```
GoTo [http://127.0.0.1:8000](http://127.0.0.1:8000) for visiting your income expense manager

For Login:

**email: user@example.com**

**password: password**

## For Contribute

- Fork the repo.
- clone it locally.
- change what you want to contribute.
- send pull/merge request


## License

The software is open-source software licensed under the [MIT license](https://opensource.org/licenses/MIT).
