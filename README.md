<h1><img src="https://github.com/maipbui/BookZ/blob/main/public/logo.png" width="30" height="30"/> BookZ</h1>

> BookZ is a website to find your favorite books for Google Books library.
> BookZ works just like web search. Try a search on BookZ.
> When we find a book with content that contains a match for your search terms,
> we'll link to it in your search results.

## Built with

- [React](https://github.com/facebook/react)
- [Google Books API](https://developers.google.com/books/docs/v1/getting_started)

## Features

- Browse by genre
- Basic Search
- Advanced filters
- Search by URL query parameters

## Getting Started

1. Clone the repo

```shell
git clone https://github.com/maipbui/BookZ.git
```

2.  Change the current directory to the repo folder

```shell
cd [BookZ]
```

3. Get `API_KEY` from [Google Books API](https://developers.google.com/books/docs/v1/getting_started)
4. Modify `API_KEY` in `[BookZ]/src/components/SetURL.jsx`

```shell
const API_KEY = "YOUR_API_KEY";
```

5. Install npm packages

```shell
npm install
```

6. Runs the app in the development mode.

```shell
npm start
```

## Try it out.

See Deployment with Heroku: [BookZ](https://bookz-react.herokuapp.com/)

## License

MIT license. See `LICENSE` for more information.
