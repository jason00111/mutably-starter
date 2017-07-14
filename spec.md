## Specifications

- [X] Your repo is a fork of [mutably-starter](https://github.com/GuildCrafts/mutably-starter).
- [X] Your repo has a README with instructions for how to run your project.
- [ ] Your app is SPA (single page app). All CRUD actions take place on the same page, preferably the root (`/`) route.
- [ ] All interaction with the API happens with jQuery's AJAX function -- don't submit data via forms. You can use `form` html tags, but do all your form submission in your `js`. Make use of jQuery's `event.preventDefault()`.
- [ ] A user can read and display all the data for a resource.
- [ ] A user can create a new item via a create form. When the user creates a new item, that item should either get appended to the page or all the items should get re-retrieved in the `js`. No full page refresh.
- [ ] A user can update an existing item. Updating happens inline. This means that there is an edit button next to each item that, when clicked, the item text gets replaced with an pre-populated editable, input field. And the edit button becomes a save button. Once the save button is clicked and success message comes back from the server, then then input gets replaced with the updated text. No page refresh.
  For example, this: <br>
  <img width="229" alt="screen shot 2017-05-11 at 3 26 09 pm" src="https://cloud.githubusercontent.com/assets/3010270/25974508/4ac57980-365e-11e7-8b1f-6cf9eefaac22.png">
  <br>
  becomes:
  <br>
  <img width="253" alt="screen shot 2017-05-11 at 3 26 18 pm" src="https://cloud.githubusercontent.com/assets/3010270/25974512/5024433e-365e-11e7-802f-c60afacddecd.png">
  <br>
  When the user clickes the edit button.
- [ ] A user can delete an existing item via a delete button next to each item. No page refresh.
- [ ] Use a UI library to make your site look nice.
- [ ] The artifact produced is properly licensed, preferably with the MIT license.
- [ ] App is deployed on Heroku.

### Stretch

- [ ] Create another version of your front-end using a front-end framework such as React or Angular.
