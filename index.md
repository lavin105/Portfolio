<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>Document</title>
    <link rel="stylesheet" href="index.css" />
  </head>
  <body>
    <header id="section1">
      <nav>
        <div class="logo" ><a href="#section1">Brandon Lavinsky</a></div>
        <ul>
          <li><a href="#section2">About</a></li>
          <li><a href="#section3">Projects</a></li>
          <li><a href="#section4">Photos</a></li>
          <li><a href="#section5">Contact</a></li>
        </ul>
      </nav>
      <div class="main_heading" >
        <h1 class="me">
          Hello my name is<strong class="b"> Brandon Lavinsky</strong>
        </h1>
        <h3 class="me_sub">
          Welcome to my portfolio
        </h3>

        <div class="hot_links">
          <div class="holder">
            <a href="https://github.com/lavin105" target="_blank"
              ><img src="./images/github_logo.svg" alt=""
            /></a>
          </div>
          <div class="holder">
            <a
              href="https://www.linkedin.com/in/brandon-lavinsky-6bb2b4133/"
              target="_blank"
              ><img src="./images/linkedin.png" alt="" class="bigger2"
            /></a>
          </div>
          <div class="holder">
            <a href="./images/resume/Resume.pdf" download="Resume"><img src="./images/res.png" alt="" class="bigger"/></a>
          </div>
        </div>
        <div class="arrow_down"></div>
      </div>
    </header>
    <main >
      <a name="section2"></a>
      <section class="about">
        <h1 >About Me</h1>

        <div class="about_container">
          <div class="info">
            <div class="icon_logo">
              <img src="./images/info_icon.jpg" alt="" />
            </div>
            <div class="education">
              <h3>Brandon Lavinsky</h3>
              <p>
                I'm a Software Engineer from Southern California with a passion
                for web development, photography, and anything and everything
                outdoors
              </p>
            </div>
          </div>
          <div class="info">
            <div class="icon_logo">
              <img src="./images/chapman_logo.png" alt="" />
            </div>
            <div class="education">
              <h3>Chapman University</h3>
              <p>BS Software Engineering<br />Minor in Analytics</p>
            </div>
          </div>
          <div class="info">
            <div class="icon_logo">
              <img src="./images/hobies.svg" alt="" />
            </div>
            <div class="education">
              <h3>Hobbies</h3>
              <p>Surfing<br />Photography<br />Drawing<br />Hiking</p>
            </div>
          </div>
        </div>
      </section>

      <section class="projects" id="section3">
        <h1>Projects</h1>

        <div class="projects_container">
          <div class="project">
            <div class="project_description">
              <div class="title">
                <h2>Campaignify</h2>
                <div class="mini_git">
                  <a href=" https://github.com/ChapmanCPSC/SE-498_01"><img src="./images/github_logo.svg" alt=""/></a>
                </div>
              </div>
              <p>
                Mobile voter canvassing tool developed for the mayor of Costa
                Mesa to aid in collecting relevant voter data in preparation for
                elections.
              </p>
              <p class="tech">-React -Ruby -GraphQL -Docker</p>
            </div>
          </div>
          <div class="project">
            <div class="project_description">
              <div class="title">
                <h2>Recipe Whiz</h2>
                <div class="mini_git">
                  <a href="https://github.com/lavin105/RecipeManagementApp"><img src="./images/github_logo.svg" alt=""/></a>
                </div>
              </div>
              <p>
                Android app created with the vision of eliminating the need for
                paper recipes.
              </p>
              <p class="tech">-Android -Java</p>
            </div>
          </div>
          <div class="project">
            <div class="project_description">
              <div class="title">
                <h2>Housing Helper</h2>
                <div class="mini_git">
                  <a href="https://github.com/lavin105/HousingDatabase"><img src="./images/github_logo.svg" alt=""/></a>
                </div>
              </div>
              <p>
                Command line interface tool developed to help student find
                housing for their college campus.
              </p>
              <p class="tech">-Java -JDBC -MySQL</p>
            </div>
          </div>
        </div>

        <div class="go">
          <h3>Check out my Github for more projects!</h3>
          <a href="https://github.com/lavin105" download="Resume" class="to_git">https://github.com/lavin105</a>
        </div>
      </section>

      <section class="photos" id="section4">
        <h1>Photography</h1>

        <div class="photos_container">
          <div class="photo">
            <img src="./images/gallery/flower.JPG" alt="" />
          </div>
          <div class="photo">
            <img src="./images/gallery/lake.JPG" alt="" />
          </div>
          <div class="photo">
            <img src="./images/gallery/pool.JPG" alt="" />
          </div>
        </div>
      </section>

      <section class="contact" id="section5">

        <h1>Contact Me</h1>
        <h3>Email</h3>
        <h4>-brandonlavinsky@gmail.com</h4>
        <h4>-lavin105@mail.chapman.edu</h4>
        <h3>Phone</h3>
        <h4>-(310)-972-0622</h4>
        </h4><br/>
        <br/>




      </section>
    </main>
  </body>
</html>
