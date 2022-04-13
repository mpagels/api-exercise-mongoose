# API exercise

You are assigned creating a book store `API` with `express` and `mongodb`

This `API` should

- return all saved books
- return a single book by id
- can save a new book
- can remove a book by id
- can modify a book by id

All books should saved in a local mongo database on your local machine. Nothing should be deployed. This is just for training purpose.

## Schema

A book should contain the following information

- titel (required)
- isbn (required)
- author name (required)
- description
- publisher (required)
- number of pages
- published date (required)

`required` means, when you add a book to your `API` these are information that have to be provided. If not, an error is send back.

### Example

If I would ask the `API` for a book, the response would by a `JSON` looking like this:

```json
[
  {
    "title": "Harry Potter und der Stein der Weisen ",
    "isbn": "3551551677",
    "author": "Joanne K. Rowling",
    "description": "Bis zu seinem elften Geburtstag glaubt Harry, er sei ein ganz normaler Junge. Doch dann erfährt er, dass er sich an der Schule für Hexerei und Zauberei einfinden soll - denn er ist ein Zauberer! In Hogwarts stürzt Harry von einem Abenteuer ins nächste und muss gegen Bestien, Mitschüler und Fabelwesen kämpfen. Da ist es gut, dass er schon Freunde gefunden hat, die ihm im Kampf gegen die dunklen Mächte zur Seite stehen.",
    "published_date": "1998-01-01T23:00:00.000Z",
    "number_of_pages": 335,
    "publisher": "Carlsen"
  }
]
```

## Recources

- [How the web works](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)
- [CRUD (HTTP) Methods][https://restfulapi.net/http-methods/]
- [express.js](https://expressjs.com/)
- [mongo](https://www.mongodb.com/docs/manual/)
- [mongoose](https://mongoosejs.com/docs/index.html)

## Bonus exercise (#1)

- Create a React app that retrieves your book API and displays all books in a list

## Super bonus exercise (#2)

- Create a `create` page, where you can add a new book to the database
- [post json data with fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch#uploading_json_data)

## Super mega bonus exercise (#3)

- Dance!
