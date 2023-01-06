# Quiz

A front-end `ANGULAR` programming exercise by TEAMBER.

## The job

Your job is to write the logic for a quiz system. This is a completely standard quiz with multiple levels of difficulty that you've probably encountered many times in your life, so the way it works should be immediately familiar to you.

We have provided a file containing questions for each level of difficulty to use in creating the quiz. The rest is up to you.

We recommend that you fork this repository and work on GitHub.

## Your tasks

* Create a nice and simple interface, using `all the values available` in a question
* Write the quiz logic:
  * Allow selection of one of three difficulties, `beginner`, `confirmed`, `expert`.
  * Depending on the chosen difficulty, pick a random question from `that difficulty`.
  * Display the question in the interface with the available answers.
  * When the user clicks on one of the available answers:
    * `Check` if the answer is correct,
    * `Notify` the user if he's right or wrong,
    * `Increment` a correct answer counter,
    * `Move on` to the next question.
  * Repeat these steps `until all questions have been picked`
* Once the quiz is complete you will be presented with :
  * An interface with the `score` including the number of correct answers out of the number of questions,
  * A `history` summary of the quiz, allowing you to see the answers.

## Notes

* You must use the `quiz.ts` file in `assets/data` directory,
* No libraries are allowed, everything must be done from scratch,
* Respect as much as possible the conventions and good practices,
* You are completely free on all aspects of design and integration,
* Once the exercise is finished, make your code available on GitHub
