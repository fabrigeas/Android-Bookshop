# location Manager

## Description

    This is an android app that enables a user to search books, add books to the cart, borrow and return books from 3 book shops.

    The books in the bookshop are being managed by another app (website).

    A User donwloads the app, creates an accout, searches a for a book,
    selects a book to view details, then decide to add a book or several books to a cart.

    The user can then view his cart and decide to 
        - checkout (borrow) a book from the cart (The number of available books is the automatically updated ),

        - if the book is not available to  checkout, the user can reserve it and  and be added to the wait queue for checkout a soon as a copy is available.

        - delete a book from the cart.

    The user can view his borrowed books and
        - return a borrowed book.

    The user can then view his history (returned books).

## The code

    The app is written in Android native using java.
    The backend is written in
        - js
        - node
        - express
        - mongodb

## Quickstart setup installation

    Currently the app can only run using a test server (localhost).

### Running the app using the localhost

    - Clone/download the node server
    - Navigate with the shell/cmd to the root of the server
    - run the following npm commands one after the other
        $ npm install
        $ npm start
    - The server is running.
    - now obtain the ip address of the server by running 
        $ ipfonfig #shell
        $ ifconfig #cmd
    - Use this ip address in your app, make sure the server and the phones are in the same homegroup (network).

## Screenshots

Search a book

![search-book](/screenshots/home.jpg) ![search-book](/screenshots/book-search.jpg) ![book-detail-in-search](/screenshots/book-detail.jpg) 
-----------------------------------------------------------------

Book detail view

![book-in-cart](/screenshots/confirmation.jpg)

----------------------------------------------------------------
Sign in/up

![Side menu](/screenshots/side-menu.jpg) ![sign-in](/screenshots/sign-in.jpg) ![sign-up](/screenshots/sign-up.jpg)
----------------------------------------------------------------
