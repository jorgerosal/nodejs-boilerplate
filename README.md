# A NodeJs Project Kickstarter Biolerplate
Clean and minimalistic boilerplate to start your NodeJs project.

### ⭐ Good for
  - Building a worker scripts.
  - Building scripting and automation tool.
  - Stand-alone, fully customizable project.
  - Creating clean file structured project.
  - Following standard naming conventions so collaborators/team8s can understand easily your code.

### 📘 Prerequisites
 - NodeJs Installed in your local environment.
 - .env file -- Yes you need this!

### 📝 Usage
1. Clone the repo to your local environment.
  - On the command prompt run the following commands:
    run ```git clone https://github.com/yortrosal/nodejs-boilerplate.git ```
    then ```cd nodejs-boilerplate ```
2. run ```npm install``` to install initial dependencies.
3. Make sure you have .env file available.
   Or generate one:  ```cp .env.example .env``` (edit it with your secret keys and other credentials)
4. Once you have the .env file setup in the main directory.
5. run ▶️ ```npm start``` to start the program. It will run the script from the app.js file.
6. Modify the package.json file. Edit the project name and other stuff.
7. Finally, start and build your application scripts. Customize your project however you like.

###  📘 Why is it important to use env file?
It has variety of usage. Find out [more](https://codeburst.io/process-env-what-it-is-and-why-when-how-to-use-it-effectively-505d0b2831e7).
But the sole purpose of using .env file for our project is to secure our credentials such as logins, api keys, and other important stuff. It is important not to include your .env file when you in our repository specially when your project is public. It's easy

### Accessing your credentials from .env file.


## 🏗 Project Structure
    nodejs-boilerplate
      ├── core
      │   ├── custom-subfolder-example
      │   │   ├── example1.js
      │   │   ├── example2.js
      │   │   └── example3.js
      │   │
      │   ├── your-script.js
      │   └── hello-world.js
      │
      ├── .env.example
      ├── .env
      ├── .gitignore
      ├── package.json
      └── README.md

### 💬 Tech Support
  - If things went wrong, google it first. People ahead of you have had similar issues in the past and solved it.
  - Last resort. -- Contact Jorge. He'd be happy to help you.

### 🎩 Authors
  - Jorge Rosal - [GitHub](https://github.com/yortrosal)
  - your name here...

### 📜 License
The MIT License (MIT) Jorge Rosal
