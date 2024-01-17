## TailwindCss with Docker

### Nike shoes promo page


<!-- [Visit site](https://tailwindcss-nike-sxidsvit.vercel.app/) -->

---

![](demo.gif)

### How to use docker & docker-compose to run this project

```js
// for development
docker build -f Dockerfile.dev -t tailwindcss-nike-dev .
docker run -d -p 5173:5173 --name tailwindcss-nike-container-dev tailwindcss-nike-dev 

// for production
docker build -f Dockerfile.prod -t tailwindcss-nike-prod .
docker run -d -p 8000:80 --name tailwindcss-nike-container tailwindcss-nike-prod  

// for docker compose
docker-compose -f docker-compose.yml up --build

docker image inspect tailwindcss-nike

```


---
##### Contact with me: 
[<img alt="webDev | LinkedIn" src="https://img.shields.io/badge/linkedin-0077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />][linkedin]

[linkedin]: https://www.linkedin.com/in/sergiy-antonyuk/

##### I can't express how much I have learned from [JavaScript Mastery ](https://www.youtube.com/c/JavaScriptMastery) & [Umair](https://www.youtube.com/@ProgrammingwithUmair321) ! <br> Thanks for the hard and smart work.
