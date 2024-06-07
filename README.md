Using BDD within CucumberStudio I have created 5 scenarios to test https://www.saucedemo.com/v1/index.html

[![Hiptest Status](https://studio.cucumber.io/badges/folder/3864515)](https://studio.cucumber.io/projects/444893/test-plan/folders/3864515)

**Test goal**
To ensure that the main functionality of the site is adequately covered.
Main functions being:
- Login
- Checkout
- Cart Count
- Add/Remove items from the cart

1. **Contents**
   - 3 subfolders
   - 5 scenarios
   - 'Standard user login' contains tests for the 4 provided usernames with datatable links
   - 'Open item page' contains tests for 6 items stored with datatable links
   - A link to the project is included on this readme and the Gherkin scripts have been included on the Main branch of this repository

2. **Testing approach**
   - Folders have been divided by basic functionality
   - Two users required distinct tests: locked out users will display an error message that will need to be checked
   - Logout and checkout functionality has been tested for any relevant users
   - In lieu of documentation, assumptions have been made on any relevant areas according to common development practices, i.e. locked out error messages
   - All functional areas within the demo page have been covered aside from social media links and filter - UI elements not strictly related to overall testing goal
