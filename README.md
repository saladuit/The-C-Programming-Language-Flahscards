# The C Programming Language Fashcards

## Welcome!
This is an open source project to make the definitive flashcard standard of the book: The C Programming Language. To achieve this I need your help to make it as simple, educational and accurate as possible. Tips for contributing to this project:
  - try to make the cards as simple as possible so that it is easy to remember e.g. by using cloze cards or by using the Immage Occlusion addon
  - Cards should be made in their approiate deck. e.g. a flashcard with keywords as theme could be placed in Appendix A - Reference Manual Deck -> 02 Lexical Tokens Deck-> 04 Keywords Deck
  - Have fun learning the cards and contributing to the knowledge of others
  - More TBA

## Deck Structure
![Deck Structure](https://github.com/saladuit/The-C-Programming-Language-Flahscards/blob/4c5ce6a0c36b704136a746f5a0843d74aff89c36/media/deck_structure.png "deck_structure")

### Add-on [CrowdAnki](https://desktop.github.com/)
  - Check his project page to find the GUI intructions - Github Desktop

### Required Add-on [Image Occlusion Enhanced](https://ankiweb.net/shared/info/1374772155)
### CLI workflow

#### To start working on the deck you need to:

1. Install git on your machine.
2. Clone the repository:

    ```
    git clone git@github.com:saladuit/The-C-Programming-Language-Flahscards.git
    ```

3. [Import the deck](#import).

If you **just wants to use the deck** you can [import decks directly from there](#import-from-git).

#### How to upload changes

When you want to upload changes you've made to the GitHub, you need to:

1. Get the latest changes from the GitHub:
   
    ```
    git pull
    ```
2. [Import the deck](#import) to combine changes you've made the project.
3. Export the deck the same directory where your repository is located so that export will overwrite media directory and JSON file in the repository. (As an alternative you can export it elsewhere and copy JSON file and media directory yourself to overwrite the ones that are in repository directory.)
4. Add the changes to the repository:

    ```
    git add *
    git commit -m "new updates"
    ```
5. Upload changes you've made to the GitHub:

    ```
    git push origin master
    ```

If you just want to **get latest changes** - you need to perform only steps 1 and 2.

## Contact
safoh@student.codam.nl
