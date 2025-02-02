# Search_Engine

In this project, we refer to a library as any database containing a sufficiently large number of text documents. One such example is The Gutenberg Project, where documents are stored in various formats, including ASCII text format. Much like The Gutenberg Project’s database, a library can store tens of thousands of text documents.

A search engine in such a library is a web/mobile application whose primary feature is to point its users to the right document according to a keyword search. Another feature could be to recommend documents based on the user's search history.

We use **Spring Boot** to create the back end and **Next.js** to create the front end for this web app.

![Search Engine Screenshot](https://github.com/user-attachments/assets/c77067e2-166b-4a1c-bfbf-bdd03e4045b0)

## Requirements
For building and running the application, you need:

- **JDK 1.8**
- **Maven 3**
- **Node.js version 10.13 or later**
- **1.5GB of free disk space** for downloading 1680 books

## Demo

## Running the Application Locally

### Starting the Back End
1. Navigate to the back-end directory:
   ```sh
   cd book_search_engine
   ```
   Or use an IDE (Eclipse, IntelliJ IDEA, VS Code...) to open this folder.

2. Before running the back end for the first time, create a `books` folder to store the text files of 1680 books.

3. There are several ways to run a Spring Boot application on your local machine. One way is to execute the main method in the `com.sorbonne.book_search_engine.BookSearchEngineApplication` class from your IDE.

4. Alternatively, you can use the Spring Boot Maven plugin:
   ```sh
   mvn spring-boot:run
   ```
   The program will start downloading 1680 books from Project Gutenberg. The download time depends on your network speed.

### Starting the Front End
1. Navigate to the front-end directory:
   ```sh
   cd book_search_engine-front-end
   ```
   Or use an IDE (VS Code, WebStorm...) to open this folder.

2. Ensure the back end is running, then start the front end:
   ```sh
   npm run dev
   # or
   yarn dev
   ```

3. Open [http://localhost:3000](http://localhost:3000) in your browser to see the result.

## API Documentation
See our Postman API documentation.

## License
Released under the **MIT License**.
