remote_theme: pages-themes/cayman@v0.2.0
plugins:
- jekyll-remote-theme # add this line to the plugins list if you already have one

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Data Analyst Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <script src="script.js" defer></script>
</head>
<body>
    <div class="sidebar">
        <h2>Portfolio</h2>
        <nav>
            <ul>
                <li><a href="#about">About Me</a></li>
                <li><a href="#powerbi">Power BI Dashboards</a></li>
                <li><a href="#excel">Excel Projects</a></li>
                <li><a href="#sql">SQL Projects</a></li>
                <li><a href="#python">Python Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </div>
    
    <div class="content">
        <section id="about">
            <h1>About Me</h1>
            <p>I am a passionate data analyst with expertise in transforming raw data into actionable insights. My skills include data cleaning, exploratory data analysis (EDA), dashboard creation, and advanced analytics using Python and SQL.</p>
        </section>

        <section id="powerbi">
            <h1>Power BI Dashboards</h1>
            <div class="project">
                <h2>Canada Weather Report</h2>
                <p>This dashboard provides an interactive visualization of weather trends across Canada.</p>
                <a href="https://app.powerbi.com/view?r=eyJrIjoiZjllOTEwNTMtM2U5My00YmVjLTgwYTktOWQ2YWNkNzQ4NTFmIiwidCI6IjE3MjhiMjgzLTlhYWItNDhiNi04YjAwLTI2OTQxYTI5MzkxMCJ9" target="_blank">View Dashboard</a>
            </div>
        </section>

        <section id="excel">
            <h1>Excel Projects</h1>
            <div class="project">
                <h2>Vancouver Crime Analysis</h2>
                <p>Cleaning and analyzing Vancouver crime data to identify trends.</p>
                <a href="https://1drv.ms/x/c/c34fb1dec43df6dc/Ef89l6rpG5dKvrZeLjSdq-kBp2kwuWUZlBSmbIn6Qud5Pg?e=SSxjpj" target="_blank">View Project</a>
            </div>
        </section>

        <section id="sql">
            <h1>SQL Projects</h1>
            <div class="project">
                <h2>Conference Database</h2>
                <p>A database project for managing conference data, including attendees and schedules.</p>
                <a href="https://github.com/your-username/your-repo-name/blob/main/Conference_db(sql).ipynb" target="_blank">View Project</a>
            </div>
        </section>

        <section id="python">
            <h1>Python Projects</h1>
            <div class="project">
                <h2>Data Cleaning and Analysis</h2>
                <p>A Python project demonstrating data cleaning and analysis using Pandas.</p>
                <a href="https://github.com/your-username/your-repo-name/blob/main/data_cleaning_analysis.ipynb" target="_blank">View Project</a>
            </div>
        </section>

        <section id="contact">
            <h1>Contact</h1>
            <p>Feel free to reach out!</p>
            <ul>
                <li><a href="https://www.linkedin.com/in/gift-ajayi-036329ba/" target="_blank">LinkedIn</a></li>
                <li><a href="https://medium.com/@ajayigift.gg" target="_blank">Medium</a></li>
                <li>Email: your-email@example.com</li>
            </ul>
        </section>
    </div>
</body>
</html>
