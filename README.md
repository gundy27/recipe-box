# The Recipe Box

The Recipe Box is a culinary social media site that is intended for small, close-knit groups such as families. We all know that Grandma has the best recipes, but she doesn't have any way to easily share her recipes in a virtual way. The Recipe Box site enables family members to join a group where they can exchange their favorite recipes and try out recipes that their fellow group members post. This site provides a great way for families to still share a dinner experience together, even if they are physically separated. 

As user numbers increase, the site can be used to sell ad space and/or promote specific kitchen appliances, tools, ingredients etc. 
 
## UX
 
Simple and sweet, just like mom's cooking. That is the focus of this site, not too complicated, very intuitive and easy to navigate. The user should be able to easily post, read, edit, and delete the recipes that they have created as well as search and read recipes from other users in their group. To keep things simple, the site will be modeled in a similar fashion to a blog, where newer recipes are at the top of a "recipe feed". Here are some sample user stories that will drive some of the main features that will be built for The Recipe Box:

### User stories

- As a user, I want to be able to fill out a form that saves my recipes, so that I can view them at a later time
- As a user, I want to be able to search for recipes based on keywords in the title, instructions, or ingredients, so that I can easily find recipes that I am craving
- As a user, I want to be able to assign a rating to my recipe, so that I know if I enjoyed it or not when I review it later

### Wireframe
(To be included)

## Features
The features all work to deliver a collective culinary blog that can be easily navigated and searched to present the desired results. 
 
### Existing Features
- Feature 1 - Create new recipe: This feature will open a new page that presents the user with a form that they can fill out with all the required fields needed to recreate a recipe
- Feature 2 - Search: This feature will enable users to search the MongoDB based on the title, ingredients, and description fields to filter the recipes and present only matching recipes
- Feature 3 - User accounts: This feature will allow other users to see who has created a specific recipe and can also be used to associate other recipes with different user accounts
- Feature 4 - Calendar: Users can sign up for reminders on specific days to post a recipe for the rest of the group to make


### Features Left to Implement
- See schedule of recipes
- Rate recipes
- Attach photos to recipes
- User inbox
- Recipe categories

## Technologies Used

- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.

- [Flask]

- [MongoDB]

- [CSS]

- [HTML]

- [Materialize]


## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment

Heroku

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for **environment** variables (Heroku Config Vars)?
- Different configuration files?
- **Separate git branch?**

In addition, if it is not obvious, you should also describe how to run your code locally.

## Credits

### Templates
https://startbootstrap.com/previews/modern-business

### Content
- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

### Media
- The photos used in this site were obtained from ...

### Acknowledgements

- I received inspiration for this project from X