# End to End E-commerce Website testing using Playwright.

Done this E2E eCommerce website testing to have an experience in UI automation testing. The below links are a playlist of all the testing which I have done. 

[Testing Demo link](https://youtube.com/playlist?list=PLLpEWf3xwiC98pPryIblITZB_0nuU7snQ)


## Test description

1. UI controls, Child window handling, Keyboard / mouse actions, Login error validations.
2. Clients login using different credentials, Placing order for 2 different clients.
3. API tests: Validation of success order creations.
4. Network security test: User can't access another user's orders using their order ID.
5. Visual tests: Pop-up validation, Visual comparison.

## Prerequisite
 Ensure `node` and `npm` is installed in the system

## Steps to run the test 

1. Clone the repo
2. Run `npm install` in root directory of the repo
3. Run `npx install playwright` if playwright is not there in system
4. Run `npx playwright test` in root directory of the repo
5. Headless can be set `false` in `playwright.config.js`. Hence it will run with visualization
6. Run `npx playwright show-report`


