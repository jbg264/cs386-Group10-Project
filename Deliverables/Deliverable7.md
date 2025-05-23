# Deliverable 7 Report
## Developers: Ryan Wood, Latisha Talayumptewa, Blase Gornick, Jeremiah Lopez, Brian Dorame, Alyssa Sombrero


 <!--Provide 1-2 paragraphs to describe your system. This will help us to remember what your system is about. 

Grading criteria (1 point): completeness, language. -->
### Description
Film Haven is a streaming entertainment website that allows indie film enthusiasts to easily watch the most recent and popular indie films created by independent creators, prioritizing the customer needs by curating the website to their interests and encouraging community engagement.  By visiting Film Haven, users can experience innovative films and support small movie businesses and independent creators. Film Haven is a indie movie review website that allows film enthusiasts and aspiring indie filmmakers to discover, showcase, and review unique and compelling indie films. 

The system must support user account creation and management, allowing users to securely register, login, and update their bio and favorite genres. Publishers update their profile to include the bio, genre specialization and website link and need a simple process to submit their movie for assessment by admins, ensuring it is following platform guidelines. The system must also provide personalized recommendations generated from the user's favorite genres to help the user discover new indie films based on their viewing history and preferences. Additionally, users should be able to create and manage Watchlists and mark films as Favorites for easy access. The platform must include a review system, allowing users to add ratings and comments to movies, creating community engagement through comments and interactions. Admins must have the tools to review and approve film submissions and ban users to regulate platform rules. Finally, movies should be easily searched for by the user, using various criteria such as genre, year, rating, and title, allowing for a seamless and engaging experience for all stakeholders.

<!-- Verification aims to ensure that you correctly developed the product. 

For this deliverable, show an example of a unit test that uses mock objects to isolate the class from the rest of the system. 

Test framework you used to develop your tests (e.g., JUnit, unittest, pytest, etc.)
Link to your GitHub folder where your automated unit tests are located.
An example of a test case that makes use of mock objects. Include in your answer a GitHub link to the class being tested and to the test.
A print screen showing the result of the unit tests execution. 
Grading criteria (5 points): adequate choice of a test framework, coverage of the tests, quality of the tests, adequate use of Mock objects, and a print screen showing successful test execution. -->
### Verification

### Test Framework Used ###

- For the automated unit tests, we used Jest, a popular JavaScript testing framework known for its speed, reliability, and built-in mocking capabilities. Jest is widely used for testing frontend and backend JavaScript applications, making it an ideal choice for our project.

#### Link to automated unit tests: [__tests__](https://github.com/rmwood367/cs386-Group10-Project/tree/dev6_test/project/__tests__)

### Example Test Case Using Mock Objects ###

Below is an example of a test case using mock objects, specifically for mocking `localStorage` and `fetch` calls in Jest.
Link [here](https://github.com/rmwood367/cs386-Group10-Project/blob/main/project/__tests__/script.test.js).
```
PS C:\Users\bdora\Documents\cs389project\cs386-Group10-Project\project> npx jest __tests__/script.test.js
  console.log
    BioForm submit event triggered!

      at HTMLFormElement.log (__tests__/script.test.js:18:15)

 PASS  __tests__/script.test.js
  BioForm Submission
    √ should correctly call `localStorage.getItem('userId')` on form submission (72 ms)

Test Suites: 1 passed, 1 total
Tests:       1 passed, 1 total
Snapshots:   0 total
Time:        2.736 s
Ran all test suites matching /__tests__\\script.test.js/i.
```









<!-- An acceptance test is a test that verifies the correct implementation of a feature from the user interface perspective. An acceptance test is a black box test (the system is tested without knowledge about its internal implementation). Provide the following information:

Test framework you used to develop your tests (e.g., Selenium, Katalon Studio, Espresso2, Cucumber, etc.)
Link to your GitHub folder where your automated acceptance tests are located.
An example of an acceptance test. Include in your answer a GitHub link to the test and an explanation about the tested feature.
A print screen/video showing the acceptance test execution. 
Grading criteria (7 points): adequate choice of a test framework, coverage of the tests, quality of the tests, adequate example of an acceptance test, print screen/video showing successful tests execution. -->
### Acceptance Test

We used Katalon Studio to perform Acceptance Testing.

Our Folder:
https://github.com/jbg264/cs386-Group10-Project/tree/ac918b07585013f3a9ee2ac99ee53b4c1bae94da/Acceptance%20Testing


In this scerenshot, we are testing if an invalid login will fail. The test passes, meaning this system is working as intended. 

https://github.com/jbg264/cs386-Group10-Project/blob/ac918b07585013f3a9ee2ac99ee53b4c1bae94da/Acceptance%20Testing/FailedLoginText
![Screenshot 2025-04-27 210411](https://github.com/user-attachments/assets/1b2f500b-1746-4751-ac51-24bcf56618ce)
<!-- At the beginning of the semester, you talked to the clients/potential users to understand their needs. Now it is time to check if you are on the right track by conducting some user evaluation on the actual system. Include in this deliverable the following information:

Script: The script should have the tasks that you gave to the user, what data you collected, and the questions you asked. In particular, do not forget to add questions about the users’ general impressions. You can ask open questions (e.g., How would you describe the homepage of our app? How do you compare our system to the competitor X?) or closed questions (On a scale of 1 to 10, how would you rate the layout of our application? On the same scale, how likely would you use the system in its current state?). Take a look at the inception and requirements deliverables to help create the script. Design a script to check if you are achieving your initial goals and if the features are implemented in a satisfactory way. 

Results: Conduct the user evaluation with at least 3 users. Report the data that you collected.

Reflections: Reflect on what you observed. Some questions that you can explore: What features worked well? What can be changed? How is the learning curve of your system? Did the users perform the tasks as you expected? Did the users’ actions produce the results they expected? What did the users like the most? Is your value proposition accomplished? 

Grading criteria (17 points): adequate script, adequate report of the results, adequate reflection, language. -->
### Validation
**Script:**
For our user evaluation, we created a script to assess if FilmHaven is meeting our inteded goals. Designing the script to assign tasks and questions based on our requirements to validate our progress. 

**Tasks:**
 1. Create a new account on FilmHaven
 2. Update your profile
 3. Search for a indie film in your preferred genre
 4. Mark a film as a favorite
 5. Write a review and post it for a movie
 6. Explore the homepage
 7. Try to add a friend

**Data Collection:**
 - Observation notes during task completion
 - Time taken to complete each task
 - Number of errors or difficulties encountered
 - User comments during the process

 **Questions:**
 - Can you find the movie "blank" in the website?
 - Would you find the website design pleasing and how? If not, can you share some improvmenets we should make.
 - How does FilmHaven compare to other movie review platforms you've used like Letterboxd or IMDb for example
 - Would you upload your indie movie on this website and why? (if applicable)
 - Would you recommend this website to your friends who want to pursue learning more about Indie films? Why?
 - On a scale of 1 to 10, how would you rate your overall experience using this website? Could you explain what factors influenced your rating?
 - How likely are you to use FilmHaven again

 (Overall interview should take around 3 - 7 minutes)

**Results**
*Participants*
 1. Grace Benally 23 year old regular moviegoer that uses competitor apps
 2. Participant 2 - description
 3. participant 3 - description

*Task Completion Table*
| Task | Completion Time | Difficulties Noted |
| ---- | --------------- | ------------------ |
|      |                 |                    |

*Question Average*
Navigation: /10 
UI: /10
Utility: /10
Likelihood to use again: /10
Systems: /10

**Reflections:**

Features that worked well 

Areas for improvement

Learning curve of the system 

Was the system used as intended

Did users actions produce the intended results

What did the users like the most

Is our Value Proposition accomplished

