# CRUD Operations Using Reqres API

This project is an **API test automation framework** built using **Postman**, **Javscript**, and **Newman Reports** to validate the CRUD functionalities. The framework supports **CI/CD using GitHub Actions** and **generates test reports**.

## Tech Stack

| Tool/Library      | Purpose                                |
|-------------------|----------------------------------------|
| Javascript        | Scripting language                     |
| Newman Reports    | Newman HTML                            |
| GitHub Actions    | CI/CD pipeline                         |
| Postman           | UI Tool                                |
| Git               | Download online                        |


The purpose of this test plan is to validate the functionality of the Reqres API endpoints used for Create, Read, Update, and Delete (CRUD) operations using Postman. This ensures that the API behaves as expected for both positive and negative scenarios.

## Install Postman UI
Download online.

## Install Git
Download online.

## Pre-requisite:
Install node js. Download Node from internet.
Check if installed using command line.
Open CMD after installing: check if node and npm is installed:
node --version
npm --version

## Install Newman report in the folder where the repo is cloned
npm install -g newman

## Install Newman HTML extra report in the folder where the repo is cloned
npm install -g newman-reporter-htmlextra

## Running Tests Locally

### Clone the repo in the required directory on your PC if you want to run locally:

Open Gitbash or CMD:

git clone https://github.com/karanAtreya1986/RemWasteAssignment_API.git

cd path_of_the_folder_where_repo_cloned

Run test using Command Line:
newman run path_to_collection.json -e path_to_environment_file.json -r htmlextra

To see the report once it ran:
Go to the folder where the repo is cloned.
Open Newman folder.
Open the HTML report.

View the report in your browser. Reports are present in the path:
newman/_filename_.html

## How to View GitHub Actions Reports
Go to repo URL (https://github.com/karanAtreya1986/RemWasteAssignment_API.git) → Actions
Click on the latest workflow run.
Scroll to Artifacts.

Download-

Newman Report (newman-html-report)

## Contributing to repo:
Fork the repo

Create your feature branch (git checkout -b feature/add-new-test)

Commit and push

Submit a pull request
