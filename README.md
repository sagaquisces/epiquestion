# epiquestion

App is a crowdsourced repository of questions submitted by developers and answered by other developers.

##Planning

1. Configuration/dependencies
  * [Git](https://git-scm.com/)
  * [Node.js](https://nodejs.org/) (with NPM)
  * [Ember CLI](https://ember-cli.com/)

2. Specs
  * Form for question, author and additional notes. Output: In a list on the index page with a link to a detail page that has the notes (which can include HTML tags) and all the answers.
  * Form for answers on question page (/question/question_id). Output: answer appears below question in order received.
  * All questions will appear on homepage with just question and author.
  * User can edit questions.
  * User can add answers to questions.

3. Integration
  * Initial routes or index pages with all dependencies in Controller/index.html head
  * Template/html page for About.
  * Template/html page for Contact
  * Template/html page for Question (`/question/:question_id`)

4. Addons
  * Bootstrap
  * Some custom styling in `/app/styles/app.css`

## Installation

* `git clone <repository-url>` this repository
* `cd epiquestion`
* `npm install`

## Running / Development

* `ember serve`
* Visit your app at [http://localhost:4200](http://localhost:4200).

### Code Generators

Make use of the many generators for code, try `ember help generate` for more details

### Running Tests

* `ember test`
* `ember test --server`

### Building

* `ember build` (development)
* `ember build --environment production` (production)
