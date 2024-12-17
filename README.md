# MongoDB CRUD Operations for Library Collection

This repository demonstrates basic MongoDB CRUD (Create, Read, Update, Delete) operations using a "library" database and a "books" collection. The operations showcase how to manage and manipulate documents within the collection.

### 1. **Create Operation:**
- **Create a Database:** A new database named "library" is created and switched to.
- **Create a Collection:** A collection named "books" is created with the following fields:
  - `title` (string)
  - `author` (string)
  - `published_year` (number)
- **Insert a Document:** A document containing details of your favorite book is inserted into the "books" collection.

### 2. **Read Operation:**
- **Retrieve All Documents:** Fetch all documents from the "books" collection.
- **Find Specific Author:** Find and display all books where the author is "J.K. Rowling".
- **Fetch Earliest Book:** Display the book with the earliest published year.

### 3. **Update Operation:**
- **Update Published Year:** Update the `published_year` of the book titled "The Catcher in the Rye" to the current year.
- **Add a Genre:** Add a new field "genre" with the value "Mystery" to all documents in the "books" collection.

### 4. **Delete Operation:**
- **Remove Specific Book:** Remove the document where the title is "1984".
- **Delete Older Books:** Delete all books where the `published_year` is before the year 2000.

Thank You For visiting my Profile!

