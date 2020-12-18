# IndexedDB

A web page that uses IndexedDB API to give silly answers to questions, remember the answers so that the same question always returns the same answer. This page also has a graphic component using jCanvas.

The initial 8 answers are these: Maybe, Could be, Definitely not, If the weather is good, Depends on the phase of the moon, Why do you ask?, Go ask someone else, I couldn't possibly fail to disagree less.

- If the question has not been answered before, the page should choose and display an answer randomly (for the probabilistically inclined: chosen from a uniform distribution) from the set of possible answers.

- If the question has not been answered before, the user must be able to provide an answer, which the web page must then add to the set of possible answers.

- If the question has been answered before, the web page must provide the same answer it gave before. The association between questions and answers is stored in an IndexDB database so it survives reloads of the web page.

The `clear database` button the user can click to reset the database back to the initial set of answers.

*Read more about IndexedDB API [here](https://developers.google.com/web/ilt/pwa/working-with-indexeddb)*
