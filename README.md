
[![Build Status](https://travis-ci.org/Emex4gman/Team-EOS-Mini-Classroom.svg?branch=master)](https://travis-ci.org/Emex4gman/Team-EOS-Mini-Classroom)

<div align="center">

![EOS](https://res.cloudinary.com/ibefx/image/upload/v1569326155/eso2_ojj7hj.png)

<br>

</div>

# To view the final Build
- Visit [EosClassroom](https://eosminiclassroom.herokuapp.com/)
- Enjoy

# Installation Guide To run on your local evn 

- You  need `node` installed. You can download form the [Website](https://nodejs.org/en/)
- You need the `mongodb client` [here](https://www.mongodb.com/download-center/compass) select the required version and os
- Clone this repository into `any folder`  <br>

- **If you have not been added to the organization, kindly work in your forked repository and open a pull request here** <br>
- Fork the repository and push to your `staging branch`
- Merge to your `master` and compare forks with the original repository
- Open a Pull Request.
- **Read [this](https://help.github.com/en/articles/creating-a-pull-request-from-a-fork) or watch [this](https://www.youtube.com/watch?v=G1I3HF4YWEw) for more help**

```bash
git clone https://github.com/hngi/Team-EOS-Mini-Classroom.git
```

```bash
cd Team-EOS-Mini-Classroom
```

- To set the development env database
```bash
export CLASSROOMDATABASEURL=mongodb://localhost:27017/classroom
```

```bash
npm install
```

```bash
node app.js
```

```bash
Visit localhost:3000 in your browser
```

# Contribution Guide

```bash
git checkout staging
```

The template for your profile page can be found here
`Contribution.json`

- Copy the contents of that file
- Create a new line with this markup and with your slack username like so, e.g
`
"slack username":{
        "fullname": "ibebgugwu chukwuemeka",
        "stack": "Backend",
        "skills": "JavaScript, Nodejs"
    },
    `
    
- Paste the contents there
- Push to `staging` branch and open a pull request
- Wait for review

**Ensure you read this doc [here](https://docs.google.com/document/d/1TxZqGLsut4ZVJEP6xF-DZGq3goaHfQ2phF-1I3YbrNc/edit?usp=sharing) for complete instructions** <br>
Failure to do this will warant closing your pull request

