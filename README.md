<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Miel Mahmud Sifat - Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Fira+Code:wght@600&display=swap" rel="stylesheet">
    <style>
        /* General Styles */
        body {
            font-family: 'Fira Code', monospace;
            margin: 0;
            padding: 0;
            background-color: #1e1e1e;
            color: #fff;
        }

        h1,
        h2,
        h3 {
            text-align: center;
        }

        a {
            color: #36BCF7;
            text-decoration: none;
        }

        p {
            text-align: center;
        }

        img {
            max-width: 100%;
            height: auto;
        }

        /* Header */
        header {
            position: relative;
            width: 100%;
            padding: 20px 0;
        }

        /* Typing Animation */
        .typing-text {
            font-size: 30px;
            color: #36BCF7;
            animation: typing 3s steps(30) infinite;
            white-space: nowrap;
            overflow: hidden;
            border-right: 3px solid #36BCF7;
        }

        @keyframes typing {
            from {
                width: 0;
            }

            to {
                width: 25em;
            }
        }

        /* Snake Animation */
        .snake-animation {
            position: absolute;
            bottom: 0;
            left: 0;
            width: 100%;
            height: 150px;
            background: url('https://raw.githubusercontent.com/absardari/snake-scroll-animation/master/snake.gif') repeat-x;
            animation: scroll-snake 10s linear infinite;
        }

        @keyframes scroll-snake {
            0% {
                transform: translateX(0);
            }

            100% {
                transform: translateX(-100%);
            }
        }

        /* Tech Stack Icons */
        .tech-stack img {
            margin: 0 10px;
        }

        /* GitHub Stats and Trophies */
        .github-stats img {
            width: 45%;
            margin: 10px;
        }

        .github-stats p {
            margin-top: 20px;
        }

        /* Contact Section */
        .contact {
            margin-top: 30px;
            text-align: center;
        }

        /* Footer */
        footer {
            background-color: #121212;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
    </style>
</head>

<body>

    <!-- Header with Typing Animation -->
    <header>
        <h1 class="typing-text">Assalamualykum!</h1>
        <p>Welcome to my portfolio.</p>
    </header>

    <!-- Snake Animation -->
    <div class="snake-animation"></div>

    <!-- About Me Section -->
    <section>
        <h2>👨‍💻 About Me</h2>
        <p>
            🧑‍🎓 **CSE Student** at BUBT <br>
            💻 Passionate **Flutter Developer & C++ Enthusiast** <br>
            🚀 I love turning **complex problems into real apps** <br>
            🎯 Currently exploring **Advance Flutter & Firebase integration** <br>
            🛠 Always open to learning and collaboration!
        </p>
    </section>

    <!-- Tech Stack -->
    <section class="tech-stack">
        <h2>⚙️ Tools, Tech & Platforms I Use</h2>
        <p>
            <img src="https://skillicons.dev/icons?i=c,cpp,dart,python,html,css,js,ts" alt="Tech Stack" />
            <img src="https://skillicons.dev/icons?i=flutter,react,nextjs,nodejs,mongodb,firebase,express" alt="Tech Stack" />
            <img src="https://skillicons.dev/icons?i=vscode,androidstudio,git,github,postman,figma,linux" alt="Dev Tools" />
        </p>
    </section>

    <!-- GitHub Stats and Trophies -->
    <section class="github-stats">
        <h2>📈 GitHub Stats & Trophies</h2>
        <p>
            <img src="https://github-readme-stats.vercel.app/api?username=miel2793&show_icons=true&theme=tokyonight&hide_border=true" />
            <img src="https://github-readme-streak-stats.herokuapp.com?user=miel2793&theme=tokyonight&hide_border=true" />
        </p>
        <p>
            <img src="https://github-profile-trophy.vercel.app/?username=miel2793&theme=gruvbox&margin-w=10&no-frame=true&title=Stars,Commits,Followers,Repositories" />
        </p>
    </section>

    <!-- Contact Me Section -->
    <section class="contact">
        <h2>📧 Contact Me</h2>
        <p>
            <a href="mailto:mahmudsifat2793@gmail.com">
                <img src="https://img.shields.io/badge/Email-mahmudsifat2793%40gmail.com-blue?style=for-the-badge&logo=gmail&logoColor=white" />
            </a>
            <a href="mailto:20234103368@cse.bubt.edu.bd">
                <img src="https://img.shields.io/badge/Email-20234103368%40cse.bubt.edu.bd-blue?style=for-the-badge&logo=gmail&logoColor=white" />
            </a>
        </p>
    </section>

    <!-- Footer -->
    <footer>
        <p>Thank you for visiting my portfolio! 🔥</p>
    </footer>

</body>

</html>
