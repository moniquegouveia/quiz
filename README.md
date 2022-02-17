## Features
### Existing Features

- __Start Quiz Button__

In this program [Quiz App with Timer], there are three layers or boxes, and these boxes shown one by one on a particular button clicked. At first, on the webpage, there is shown a button labeled as “Start Quiz” and when you clicked on that button, then the info box appears with popup animation.

![Start Quiz Button](https://github.com/moniquegouveia/quiz/blob/main/start.png)

- __Infobox__

In this infobox, there are some rules of the quiz and two buttons labeled as “Exit” and “Continue”. When you clicked on the Exit button, the info box will be hidden but when you clicked on the Continue button, then the Quiz Box appears.


![Infobox](https://github.com/moniquegouveia/quiz/blob/main/info-box.png)

- __Quiz Box__

In the Quiz Box, there is a header with a title on the left side and a timer box on the right side. This timer starts decrement from 15 to 0 sec and there is also shown a timeline indicator that is sliding from the left to right side according to the timer. If the user selects an option between 15 to 0 sec, the timer will be stopped and all available options will be disabled.

If the user selected option is correct, the selected option color, background color changed to green and there is also shown the tick icon to inform the user that the selected answer is correct. If the user selects an option that is incorrect, the selected option color, background color changed to red and there is shown the cross icon to inform the user that the selected option is incorrect and the correct option will be automatically selected.

If the user doesn’t select an option between 15 to 0 sec, the timer will be stopped once it comes in 0 and the correct option of that question will be selected automatically. After that, there is the next button to show the next question, and there is a total of five questions on this Quiz.

In the end, the result box will be appeared and shown the user score and two buttons [Replay Quiz, Quit Quiz], if the user clicked on the replay quiz button, the quiz will again start with the number 1 question, and the score of the user will be 0 but if the user clicked on the quit quiz button, the current window will be reloaded and the quiz starts from the begin.

 ![Quiz Box](https://github.com/moniquegouveia/quiz/blob/main/questions.png)
 

## Testing 
Testing for this quiz was done using the Google Chrome Browser, using Chrome Developer Tools to check the different screensizes. Testing was also done on an iPhone 13 using Safari, as sometimes Safari can cause issues with how the website renders. No such errors were found.

-__Languages__

-HTML5
-CSS
-Javascript

### Validator Testing 


- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fmoniquegouveia.github.io%2Frecipe%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator]

## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://moniquegouveia.github.io/quiz/


## Credits 

- Instructions on Javascript was taken from [W3S Schools](https://www.w3schools.com/);
- The icons were taken from [Font Awesome](https://fontawesome.com/);
- Color scheme was taken from My Color Space ((https://mycolor.space/?hex=%23845EC2&sub=1);

**Anything more?**

Yes! We'd strongly encourage you to look at the source code of the `uptime.sh` file so that you know what it's doing. As future software developers, it will be great practice to see how these shell scripts work.

---

Happy coding!
