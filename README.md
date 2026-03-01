<h1 align="center">Ethan Carroll</h1>

<p align="center">
  I build websites and the back-end systems that power apps.
</p>

<p align="center">
  <a href="https://ethanc.org">ethanc.org</a> •
  <a href="mailto:e@ethanc.org">e@ethanc.org</a>
</p>

---

## my goal
Build high performance, durable, maintainable code that the world can rely on.

## projects
- <a href="https://github.com/ethancroll/openCalc">openCalc (terminal based calculator)</a>
- <a href="https://github.com/ethancroll/secretsHolder">secretsHolder (simple web based .env viewer)</a>
- <a href="https://github.com/ethancroll/localFile">localFile (local network file transfer)</a>
- <a href="https://github.com/ethancroll/simulation-controller">Simulation controller (flight and driving sim button box)</a>
- <a href="https://github.com/ethancroll/jobtrack">Job track (terminal based working time to earnings)</a>

## tech stack
- Next.js
- Go
- HTML, CSS, JS
---

<p align="center">
  extras, if you're interested<br>
  <a href="https://royaleapi.com/player/QYL0GYR9Y/">clash stats</a>
</p>


<div id="seconds"></div>
<div id="name"></div>
<div id="working"></div>

    <script>
        fetch('http://localhost:3000/api/mongo/read?userId=user_01KJEGG5V0P9APQ3DP1QDGYRPE')
            .then(res => res.json())
            .then(data => {
                document.getElementById('seconds').textContent = data.seconds;
                document.getElementById('name').textContent = data.name;
                document.getElementById('working').textContent = data.working;
            })
            .catch(err => console.error(err));
    </script>
