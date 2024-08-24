# my-portfolio
<!DOCTYPE html>
<html>
  <head>
    <title>Vineetha Kusam - Portfolio</title>
    <link rel="stylesheet" href="./style.css"/>
    <script src="./script.js"></script>
  </head>
  <body>
    <!-- Navigation Bar -->
    <nav>
      <div id="home">
        <div class="profile_name">
          Vineetha Kusam
          <div class="contact_info">
            <img src="html_finalprojimages/envelope.png" alt="https://icons8.com/icon/124377/circled-envelope"/>
          kusam.vineetha@gmail.com
        </div>
        <div style="clear:both;"></div>
        <div class="contact_info">
          <img src="html_finalprojimages/phone.png" alt="https://icons8.com/icon/124377/circled-envelope"/>
          +17208398093

        </div>
        </div>
        <div class="topdiv">
          <a class="topmenu" href="#about-me">About Me</a>
          <a class="topmenu" href="#skills">Skills</a>
          <a class="topmenu" href="#projects">Projects</a>
          <a class="topmenu" href="#recommendations">Recommendations</a>
          <!-- Add the links for Skills, Projects and Recommendation here -->

        </div>
      </div>    
    </nav>

    <!-- About Me -->
    <section id="about-me" class="container">
      <div>
        <img src="https://miro.medium.com/max/1400/1*qdAW1TjCN57h1lbuuzvchg.gif" class="profile_image"/>
      </div>

      <div>
          <h1>
            Hi, I'm Vineetha Kusam! <img src="html_finalprojimages/waving-hand.png" width="60px"/>
          </h1>
          <p>
            Currently , completed certification of IBM data analyst to start a new career.
            previously, worked as jr.devops engineer . I know SQL,Python,had knowledge of few technical skills like HTML , CSS and Javascript. 
            I am self-motivated and accept all the challenges that come my way .
          </p>
      </div>
    </section>
              
    <!-- Skills -->
    <section id="skills">
      <h2>Skills</h2>
      <div style="clear:both;"></div>

      <div class="all_skills">
        <div class="skill">
          <img src="html_finalprojimages/html5.png"/>
          <h6>HTML</h6>
          <p>2 years experience</p>
        </div>  

        <div class="skill">
          <img src="html_finalprojimages/js.jpeg"/>
          <h6>JavaScript</h6>
          <p>1 years experience</p>
        </div>  

        <!-- Add more skills here -->
        <div class="skill">
            <img src="html_finalprojimages/js.jpeg"/>
            <h6>SQL</h6>
            <p>1 years experience</p>
          </div>
          <div class="skill">
            <img src="html_finalprojimages/js.jpeg"/>
            <h6>Python</h6>
            <p>1 years experience</p>
          </div>    



      </div>
    </section>
          
    <!-- Projects -->
    <section class="projects" id="projects">
      <h2>
        Projects
      </h2>
      <div style="clear:both;"></div>

        <div id="projects-container" class="projects-container">
          <div class="project-card">
            <h3>Extracting and visualizing stock data</h3>
            <ul>
              <li>Using the ticker object and the function `history` extract stock information and save it in a dataframe named `tesla_data`.</li>
            </ul>
          </div>
          <hr>
          <div class="project-card">
            <h3>Data Visualzation Dashboard</h3>
            <ul>
              <li>Created data visualization dashboard , Compute graph data for creating yearly airline delay report , Computed average dataframes for carrier delay, weather delay, NAS delay, security delay, and late aircraft delay.</li>
            </ul>
          </div>
          <hr>
          <div class="project-card">
            <h3>Fashion Website</h3>
            <ul>
              <li>Created a styled multi-page website for a new player in the fashion industry and integrated it with a shopping cart, using stripe for payment gateway</li>
            </ul>
          </div>
    </div>
    </section>
    <div style="clear:both;"></div>

    <!-- Recommendations -->
    <section id="recommendations">
      <h2>Recommendations</h2>
      <div style="clear:both;"></div>
      <div class="all_recommendations" id="all_recommendations">
        <div class="recommendation">
          <span>&#8220;</span>
          Vineetha is a very quick learner and quickly grasps key concepts of Web development. 
          She got a great attitude & she is an excellent team player. 
          She has a curious mind and asks the right question. 
          She takes initiative within a team and has potentials to lead the team.
          <span>&#8221;</span>
        </div>
        <div class="recommendation">
          <span>&#8220;</span>
          Working with Vineetha has been an awesome experience. 
          She is highly knowledgable and always goes the extra step to make sure everything is right. 
          For any future projects that need her expertise I would definitely want to work with her again.
          <span>&#8221;</span>
        </div>
        <div class="recommendation">
          <span>&#8220;</span>
          I had worked along with Vineetha during the initial phase of our venture which needed Web development. 
          She is a committed resource who has in depth knowledge about the domain. 
          She will be an asset for any organisation! 
          <span>&#8221;</span>
        </div>
      </div>
    </section>

    <!-- Recommendation Form -->
    <section id="contact">
      <div class="flex_center">
        <fieldset>
          <legend class="introduction">Leave a Recommendation</legend>          
          <input type="text" placeholder="Name (Optional)"> <br/>
          <textarea id="new_recommendation" cols="500" rows="10" placeholder="Message"></textarea>
          <div class="flex_center">
            <button id="recommend_btn" onclick="addRecommendation()">Submit</button>
          </div>
        </fieldset>
      </div>
    </section>

    <div class="iconbutton">
      <a href="#home">
        <!--Add the code here for the logo to appear and the icon to be actionable-->
        <svg xmlns="https://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="white" width="63px">
            <path stroke-linecap="round" stroke-linejoin="round" d="M15 11.251-3-3m0 01-3 3m3-3v7.5M21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
        </svg>
      </a>
    </div>

    <div class="popup" id="popup" class="flex_center">
      <img src="html_finalprojimages/checkmark--outline.svg"/>
      <h3><!-- Add appropriate text here--></h3>
      <button onclick="showPopup(true)">Ok</button>
    </div>
  </body>
</html>
