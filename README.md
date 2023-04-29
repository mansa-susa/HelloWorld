<a name="readme-top"></a>

# 📗 Table of Contents

- [📖 About the Project](#about-project)
  - [🛠 Built With](#built-with)
    - [Tech Stack](#tech-stack)
- [💻 Getting Started](#getting-started)
  - [Setup](#setup)
  - [Prerequisites](#prerequisites)
- [👥 Authors](#authors)
- [🤝 Contributing](#contributing)
- [⭐️ Show your support](#support)
  -- [🙏 Acknowledgements](#acknowledgements)
- [❓ FAQ](#faq)
- [📝 License](#license)

# 📖 [Hello-microverse] <a name="Hello-microverse"></a>

**[Hello-microverse]** this was mini-projects that upkill to create a feature branch and test linters in order to have professional-looking code.

## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

  <summary>Javascript runtime environment</summary>
  <ul>
    <li><a href="https://nodejs.org/en/">Node JS</a></li>
  </ul>

  <summary>Version control</summary>
  <ul>
    <li><a href="github.com">Git Hub</a></li>
  </ul>
</details

<!-- GETTING STARTED -->

## 💻 Getting Started <a name="getting-started"></a>

Creating your first "Hello-microverse" project

To get a local copy up and running, follow these steps.

### Prerequisites

In order to run this project you need:

-A Git hub account
<br>
-Node JS
<br>
-Visual Studio Code or any other code editor of your preference
<br>
-web browser

### Setup

Clone this repository to your desired directory:<br>
Advantages of Linters:<br>

1: Catching syntax errors is more efficient. There is no need to debug simple mistakes like typos - the linter does it for you.
2: The use of linters helps to diagnose and fix technical issues—e.g. code smells—in the code. As a result, fewer defects make their way to production.<br>
3: Removes silly errors before execution and code review and allow programmers focus on logic.<br>
4: Makes codebase look like it was written by a single person.<br>
5:  Linters can help teams achieve a more readable and consistent style, through the enforcement of its rules.<br>

## Install Linters

You can find linters for most of the programming languages, e.g. Rubocop for Ruby or ESLint for JavaScript.

Also, there are many ways you can integrate a linter in your workflow:

-text editor plugin<br>
-GitHub Actions<br>
-GitHub apps<br>

## Set up Linters

**Note:** The npm package manager is going to create a node_modules directory to install all of your dependencies. You shouldn't commit that directory. To avoid that, you can create a .gitignore file and add node_modules to it:

# .gitignore

node_modules/

## Web Hint

This is a customizable linting tool that helps you improve your site's accessibility, speed, cross-browser compatibility, and more by checking your code for best practices and common errors.

**NOTE:** If you are using Windows, make sure you initialize npm to create `package.json` file.

```
npm init -y
```

1. Run
   ```
   npm install --save-dev hint@7.x
   ```
   _how to use npm: (https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)._
2. Copy [.hintrc](.hintrc) to the root directory of your project.
3. **Do not make any changes in config files - they represent style guidelines that you share with your team - which is a group of all Microverse students.**
   - If you think that change is necessary - open a [Pull Request in this repository](../README.md#contributing) and let your code reviewer know about it.
4. Run
   ```
   npx hint .
   ```
5. Fix validation errors.

### [Stylelint](https://stylelint.io/)

A mighty, modern linter that helps you avoid errors and enforce conventions in your styles.

1. Run

npm install --save-dev stylelint@13.x stylelint-scss@3.x stylelint-config-standard@21.x stylelint-csstree-validator@1.x
not sure how to use npm? Read this.

2. Copy .stylelintrc.json to the root directory of your project.

3. **Do not make any changes in config files - they represent style guidelines that you share with your team - which is a group of all Microverse students.**

If you think that change is necessary - open a Pull Request in this repository and let your code reviewer know about it. 4. Run npx stylelint "\*_/_.{css,scss}" on the root of your directory of your project.

5. Fix linter errors.

6. **IMPORTANT NOTE:** feel free to research auto-correct options for Stylelint if you get a flood of errors but keep in mind that correcting style errors manually will help you to make a habit of writing a clean code!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 👥 Authors <a name="authors"></a>

👤 **Author**

- GitHub: (https://github.com/mansa-susa)
- Twitter: (https://twitter.com/@mansa_susa)
- LinkedIn: (https://www.linkedin.com/in/faruq-hammed-931862169/)

## 🤝 Contributing <a name="contributing"></a>

<!-- FUTURE FEATURES -->

## 🔭 Future Features <a name="future-features"></a>

- [ ] **[new_feature_1]**
      Add a title 'Hello Microverse' to the title tag

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

## ⭐️ Show your support <a name="support"></a>

If you like this project, kindly leave a comment below and share it with someone who enjoys coding! Coding is all about continuous learning and allowing yourself to be a beginner. Keep going!

<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgments <a name="Microverse Inc."></a>

I'm grateful to microverse for giving me every opportunity to grow into my full potential

<!-- FAQ (optional) -->

## ❓ FAQ <a name="faq"></a>

- **[Question_1]**
  Do I have to use the vs code specifically?

  - [Answer_1]
    You can use any code editor of your chose.

- **[Question_2]**
  Where can I download node JS for installation?

  - [Answer_2]
  Node Js can be downloaded here- https://nodejs.org/en/download/
  <!-- LICENSE -->

## 📝 License <a name="license"></a>

This project is [MIT](https://choosealicense.com/licenses/mit/) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
