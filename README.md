# Welcome to My Project

## Typing Animation

```javascript
const typingAnimation = (text, outputElement) => {
    let index = 0;
    const interval = setInterval(() => {
        if (index < text.length) {
            outputElement.innerHTML += text.charAt(index);
            index++;
        } else {
            clearInterval(interval);
        }
    }, 100);
};

const output = document.getElementById('typing');
typingAnimation('Hello World!', output);
```

## The Grid Tech Stack

| Technology      | Description               |
|----------------|---------------------------|
| ![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black) | Frontend Framework       |
| ![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white) | Backend Environment      |
| ![Express](https://img.shields.io/badge/Express-000000?logo=express&logoColor=white) | Framework                |
| ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white) | Database                 |
| ![CSS](https://img.shields.io/badge/CSS-1572B6?logo=css3&logoColor=white) | Styling                  |
| ![HTML](https://img.shields.io/badge/HTML-E34F26?logo=html5&logoColor=white) | Markup Language          |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) | Programming Language     |
| ![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white) | Version Control          |

## Project Spotlight

| Project Name        | Description                      |
|---------------------|----------------------------------|
| AI_EXPENSE_TRACKER  | A tool for tracking expenses using AI  |
| MyPortfolio         | Showcase of my work              |

## Snake Game Animation

![Snake Animation](https://platane.github.io/snk/output/4.gif)

## GitHub Insights

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=sreedevrajendran&show_icons=true&count_private=true&theme=radical)
![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=sreedevrajendran&theme=radical)

## Connect with Me

[LinkedIn](https://www.linkedin.com/in/sreedevrajendran) | [Twitter](https://twitter.com/sreedevrajendran) | [GitHub](https://github.com/sreedevrajendran) | [Facebook](https://www.facebook.com/sreedevrajendran)