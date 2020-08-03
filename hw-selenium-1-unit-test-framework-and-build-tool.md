## Test structure requirements:
- [ ] Maven project
- [ ] POM xml has following sections:
  - [ ] artifact attributes
  - [ ] properties
  - [ ] dependencies
  - [ ] plugins
  - [ ] profiles
- [ ] `calculator-1.0.jar` is added as maven dependency
- [ ] TestNG is used as a testing framework
- [ ] For test maven build maven-surefire-plugin is used 
- [ ] Code conforms to the Java Code Convention
    
## File placement requirements:
- [ ] Classes should be placed into `src/test/java/hw1` package and sub-packages
- [ ] Homework should be developed in new Java classes
- [ ] Test methods' names should reflect checking functionality
    
## Tests requirements:
- [ ] You should test several Calculator operations (at least 4)
- [ ] Test for each operation should be placed in separate classes
- [ ] Create a test suite, which could run all tests
- [ ] Split test for the two groups and create a suite for each group:
  - [ ] Tests for add and subtract operations
  - [ ] Tests for multiply and divide operations
- [ ] All test data should be provided to test through the DataProviders
- [ ] Create 3 maven profiles which allow choosing test suite (by default should work profile which runs add and subtract operations tests)
