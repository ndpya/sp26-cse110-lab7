1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

**Within a Github action that runs whenever code is pushed**
This approach ensures that tests are ran consistently and that bugs/errors are caught before any code is merged. Moreover, this approach enables testing on a non-local and standardized environment, ensuring that code works outside of an individual's local machine. 

2) Would you use an end to end test to check if a function is returning the correct output? (yes/**no**)
Unit tests, that check particular components/specific functions are more helpful in this scenario since we don't want to test the entire flow of a system.