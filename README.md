## Cypress cucumber webpack typescript + Allure reports
***

Allure report is added over webpack cypress cucumber preprocessor
***

**Resources and instructions:**

cypress with webpack is [from the brain family](https://github.com/TheBrainFamily/cypress-cucumber-webpack-typescript-example)

allure report is [from @shelex](https://github.com/Shelex/cypress-allure-plugin-example)

***

**Foot Note:**
it is not possible to use allure report and cypress-cucumber-preprocessor JSON reporter at the same time. When allure is enabled, cypress-cucumber-preprocessor creates JSOn files without the failed tests.
