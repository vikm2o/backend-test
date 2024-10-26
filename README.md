
# Backend-test

- A List Page which shows a list of products

	  Each product must have the following information:
	  Product name
	  Product price
	  Product quantity
	  Product Image (You can use an image link or use any third-party image hosting provider)
- A Detail Page

		In addition to the above details, it also has a product description

## Backend API
- GET /products Route, which lists all products
- GET /products/id Route, which lists product details
- PUT /products Route to add a product

## Authentication 
    - Use JWT (JSON Web Tokens) for secure authentication.
    - Roles:
        1. View Role:
            - For List and Detail Page.
        2. Edit Role:
            - For Product Add Page

## Database
Postgresql as Database

## Unit tests
Unit tests with at least 80% Coverage

## API Tests
Tests for ALL API Routes

## Code documentation
All code should be documented

## Framework
Use SpringBoot.

## Submission
Share a Github Repo with README on how to run the project to vikash@makeit.sg
