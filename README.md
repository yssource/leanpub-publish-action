# Leanpub Publish Action
This action triggers publishing processing in LeanPub

## Inputs
### `api_key`
**Required** The api secret for your LeanPub account

### `book_slug`
Your book SLUG. It's the part of the URL for your book after https://leanpub.com/. E.g. if your book is found at https://leanpub.com/your_book, then your book's slug is your_book.

## Example usage

uses: robert-matusewicz/leanpub-publish-action@v1.0.0
with:
    api_key: <YOUR API KEY>
    book_slug: <YOUR BOOK SLUG>
