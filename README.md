<!-- Teaching and Curriculum – Dr. Fariborz Aref -->
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Teaching and Curriculum — Dr. Fariborz Aref</title>
<style>
  :root{
    --bg:#ffffff;
    --fg:#0f172a;      /* slate-900 */
    --muted:#475569;   /* slate-600 */
    --line:#e2e8f0;    /* slate-200 */
    --card:#f8fafc;    /* slate-50 */
    --accent:#1e293b;  /* slate-800 */
  }
  html,body{margin:0;padding:0;background:var(--bg);color:var(--fg);font-family:ui-serif,Georgia,Times,serif;line-height:1.5}
  .wrap{max-width:960px;margin:48px auto;padding:0 20px}
  header h1{font-size:32px;margin:0 0 6px 0;letter-spacing:.2px}
  header p{margin:.25rem 0;color:var(--muted)}
  .hr{height:1px;background:var(--line);margin:24px 0}
  .lead{font-size:18px;color:var(--accent);margin:8px 0 18px 0}
  .grid{
    display:grid;
    grid-template-columns:repeat(2,minmax(0,1fr));
    gap:16px;
  }
  @media (max-width:720px){ .grid{grid-template-columns:1fr} }
  .card{
    background:var(--card);
    border:1px solid var(--line);
    border-radius:14px;
    padding:16px 16px 12px 16px;
  }
  .card h3{margin:0 0 8px 0;font-size:18px}
  .card ul{margin:6px 0 0 1rem;padding:0}
  .card li{margin:3px 0}
  section h2{font-size:22px;margin:28px 0 10px 0}
  code, pre{font-family:ui-monospace, SFMono-Regular, Menlo, Consolas, "Liberation Mono", monospace}
  pre{
    background:#0b1220;
    color:#e2e8f0;
    border-radius:12px;
    padding:14px;
    overflow:auto;
    border:1px solid #1e293b;
  }
  a{color:#0f172a;text-decoration:underline}
  footer{margin:28px 0 8px;color:var(--muted);font-size:14px}
  .tag{font-size:13px;color:var(--muted)}
</style>
</head>
<body>
  <div class="wrap">
    <header>
      <h1>Teaching and Curriculum</h1>
      <p>Curated by <strong>Dr. Fariborz Aref</strong></p>
      <p class="lead">
        University-level materials that integrate theoretical depth, empirical rigor, and community-based learning across undergraduate and graduate sociology.
      </p>
    </header>

    <div class="hr"></div>

    <section aria-labelledby="portfolio">
      <h2 id="portfolio">Course Portfolio</h2>
      <div class="grid">

        <article class="card">
          <h3>1. Foundations of Sociology</h3>
          <ul>
            <li><a href="./Foundations_of_Sociology/Syllabus.pdf">Syllabus</a></li>
            <li><a href="./Foundations_of_Sociology/Assignments.pdf">Assignments</a></li>
            <li><a href="./Foundations_of_Sociology/Lectures/">Lecture Notes</a></li>
          </ul>
        </article>

        <article class="card">
          <h3>2. Social Problems</h3>
          <ul>
            <li><a href="./Social_Problems/Syllabus.pdf">Syllabus</a></li>
            <li><a href="./Social_Problems/Lecture_Slides/">Lecture Slides</a></li>
            <li><a href="./Social_Problems/Projects/">Student Projects</a></li>
          </ul>
        </article>

        <article class="card">
          <h3>3. Social Inequality</h3>
          <ul>
            <li><a href="./Social_Inequality/Syllabus.pdf">Syllabus</a></li>
            <li><a href="./Social_Inequality/Case_Studies/">Case Studies</a></li>
            <li><a href="./Social_Inequality/Data_Modules/">Data Modules</a></li>
          </ul>
        </article>

        <article class="card">
          <h3>4. Social Theory</h3>
          <ul>
            <li><a href="./Social_Theory/Syllabus.pdf">Syllabus</a></li>
            <li><a href="./Social_Theory/Classics/">Classic Texts &amp; Interpretations</a></li>
            <li><a href="./Social_Theory/Contemporary/">Contemporary Debates</a></li>
          </ul>
        </article>

        <article class="card">
          <h3>5. Social Statistics</h3>
          <ul>
            <li><a href="./Social_Statistics/Syllabus.pdf">Syllabus</a></li>
            <li><a href="./Social_Statistics/R_Tutorials/">R Tutorials</a></li>
            <li><a href="./Social_Statistics/Data/">Datasets</a></li>
          </ul>
        </article>

        <article class="card">
          <h3>6. Research Methods and Statistics</h3>
          <ul>
            <li><a href="./Research_Methods_Statistics/Quantitative/">Quantitative Modules</a></li>
            <li><a href="./Research_Methods_Statistics/Qualitative/">Qualitative Modules</a></li>
            <li><a href="./Research_Methods_Statistics/Mixed_Methods/">Mixed-Methods Design</a></li>
          </ul>
        </article>

        <article class="card">
          <h3>7. Community Development and Sustainability</h3>
          <ul>
            <li><a href="./Community_Development/Syllabus.pdf">Syllabus</a></li>
            <li><a href="./Community_Development/Projects/">Applied Field Projects</a></li>
          </ul>
        </article>

        <article class="card">
          <h3>8. Sociology of Health and Inequality</h3>
          <ul>
            <li><a href="./Sociology_of_Health/Syllabus.pdf">Syllabus</a></li>
            <li><a href="./Sociology_of_Health/Exercises/">Data Analysis Exercises</a></li>
          </ul>
        </article>

      </div>
      <p class="tag">All materials are prepared for undergraduate and graduate audiences with emphasis on critical reasoning, data literacy, and societal relevance.</p>
    </section>

    <div class="hr"></div>

    <section aria-labelledby="structure">
      <h2 id="structure">Repository Structure</h2>
      <pre><code>Teaching_and_Curriculum/
├── Foundations_of_Sociology/
├── Social_Problems/
├── Social_Inequality/
├── Social_Theory/
├── Social_Statistics/
├── Research_Methods_Statistics/
├── Community_Development/
└── Sociology_of_Health/</code></pre>
    </section>

    <footer>
      <div class="hr"></div>
      <p>© Dr. Fariborz Aref · Teaching and Curriculum</p>
    </footer>
  </div>
</body>
</html>

