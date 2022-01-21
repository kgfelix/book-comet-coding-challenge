# Book Comet Coding Challenge

You are hired as a software engineer to develop a new project: e-commerce called "bookcomet.com", for a book publisher.
To integrate with other systems you decide to write an API for that.

You received only the following information from the business team:

## Entities:
* Book: id, name, authors, publisher, year of publication and summary;
* BookInventory: id, book, quantity.
 
## Operations: 
* Create, Modify, Delete, list all books;
* List books by authors and publisher;
* Add to inventory, remove from inventory.

The publisher will also work with e-books. An EBook entity is similar to entity Book, with just one extra attribute: format (PDF, EPUB, etc.);

## Business rules:
* The system cannot remove a book with positive inventory;
* The system cannot have a negative inventory;
* The system cannot have duplicate books (same name and author).

## Instructions:
* You can use any programming language you like;
* You must deliver your project in a public GitHub repository;
* You can use any library you want to improve the quality of your project, just explain the reason for using them;
* Don't forget to put comments in your code and use a well-defined directory structure;
* Provide friendly error messages with the appropriate HTTP code;
* Create only the application backend, no UI is required;
* You don't need to connect with a database, use a data structure to store the data in the memory, create your own  simple structure;
* Unit tests are welcome;
