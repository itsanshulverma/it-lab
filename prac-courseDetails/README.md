# IT Practical/Lab
This is a submission as a lab work for *Paper: Internet Technology* for University of Delhi.
<br>
The live demo of this can be found on the link - https://itsanshulverma.github.io/it-lab/prac-courseDetails/
<br>
by **Anshul Verma (19/78065)**

## Problem
#### Create a plain HTML page for B. Sc. Hons CS course, mentioning details like fee, eligibility criteria, papers with names and credits, and future possibilities after the course. A button for styling should be there at bottom of the page. On clicking on this button JavaScript should redesign the complete page using jQuery in a nice presentable way.

#### index.html

```html
<!-- Written by Anshul Verma (19/78065) -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>BSc (Hons) Computer Science | Course Details</title>
  <script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>
  <script type="text/javascript">
    $(function () {
      $('#btn').click(function () {
        $("html,body").animate({ scrollTop: 0 }, 1000);
        let link = document.createElement("link");
        link.type = "text/css";
        link.rel = "stylesheet";
        link.href = "style.css";
        $("head")[0].appendChild(link);
      });
    });
  </script>
</head>
<body>
  <header>
    <img class="logo" src="arsd_log0.png" width="150px" />
    <h1>B.Sc. (Hons) Computer Science</h1>
    <h2>Atma Ram Sanatan Dharma College</h2>
    <h3>University of Delhi</h3>
  </header>
  <section class="basic-details">
    <p>
      The B.Sc. (H) Computer Science programme is designed to develop analytical & computational
      thinking, and problem solving skills. It covers the core computer science topics like computer
      systems architecture, data structures, computer networks, operating systems, computer graphics,
      algorithms, software engineering, database management, theory of computation, artificial
      intelligence, and information security. The programme builds a base for entry level jobs in
      information technology and prepares the students for higher studies in the area of Computer Science/Applications.
    </p>
    <p>The Department of Computer Science offers 3-year B.Sc. (Hons.) Computer Science programme through constituent
      colleges of the University of Delhi.
      With the new advancements in the field of computers and in a time when there is a boom in the IT industry, the
      University of Delhi has introduced B.Sc (Hons.) Computer Science,
      a 3-year undergraduate programme, for the tech-savvy youth. The colleges are contributing to the development of
      Information Technology
      by offering this programme with the help of efficient and highly qualified teachers and through well-equipped
      computer labs.
      The programme provides rigorous foundations of the concepts of Computer Science and Information Technology.
      In the final year, students also get an opportunity to do project work. Hence the combination of the concepts and
      training of software tools
      equip the students to adapt to ever-changing technology. The B.Sc. (Hons.) Computer Science programme primarily
      intends to serve as an input for
      higher degree academic programmes in Computer Science . The programme lays emphasis on building a strong
      mathematical foundation (about 30% of course work)
      and includes modules on electronics and humanities as well.
    </p>
  </section>
  <hr />
  <section class="fee-structure">
    <h2>Fee Structure</h2>
    <p>Fee for B.Sc. (Hons.) Computer Science (self financing course) is Rs. 50500/-.</p>
    <h3>Other fee and fines</h3>
    <ul>
      <li>Securities are refundable within 3 years from the date the student leaves the College.</li>
      <li>Special fee equivalent to US $100 p.a. shall be charged from the Foreign Students.</li>
      <li>College dues are to be paid ONLINE. Cash/Cheques/Pay Orders/Drafts etc., are not accepted.</li>
      <li>In case a student fails to pay his/her dues within one month of the due date as notified,
        his/her name will be struck off from the College rolls. Fine on late payment of fee is Re. 1.00 / day.</li>
      <li>Fine on Library books: General Re. 1/-per day & Overnight Rs. 2/- per day.</li>
      <li>Membership fee of Rs. 200 for the Alumni Association will be charged from IInd and IIIrd Yr. students.</li>
      <li>A fine of Rs. 100 will be imposed for loss of Identity Card.</li>
    </ul>
  </section>
  <hr />
  <section class="eligibility">
    <h2>Eligibility Criteria</h2>
    <ul>
      <li>It should be noted that there is no age bar far applying to admission at DU.</li>
      <li>Candidates are required to have passed the Class 12 or equivalent exam in order to be eligible for admission
        at DU.</li>
      <li>Candidates are required to have scored no less than 60% marks in Mathematics Class 12 or equivalent exam.</li>
      <li><b>Combination of subjects for 'Best of Four' - </b> <br>
        A total of no less than 60% marks in English, Mathematics and best of the two subjects from
        Physics, Chemistry, Computer Science/Informatics Practices.
        <br> OR <br>
        A total of no less than 60% marks in English, Mathematics and two subjects
        (other than Physics, Chemistry, Computer Science/Informatics Practices)
        with a deduction of 1% per subject in the aggregate.
      </li>
    </ul>
  </section>
  <hr />
  <section class="papers">
    <h2 class="papers-heading">Papers and Syllabus</h2>
    <div class="sem-1">
      <h3>Semester - 1</h3>
      <p>Total Credits - 22</p>
      <ul>
        <li>
          <ul>
            <h4>Core Courses:</h4>
            <li>
              <b>BHCS01 - Programming Fundamentals using C++ with Lab</b>
              <p>Credits: 4 + 2 = 6</p>
            </li>
            <li>
              <b>BHCS02 - Computer System Architecture with Lab</b>
              <p>Credits: 4 + 2 = 6</p>
            </li>
          </ul>
        </li>
        <li>
          <ul>
            <h4>Other Courses:</h4>
            <li>
              <b>General Elective - 1 with Practical/Tutorial</b>
              <p>Credits: 4/5 + 2/1 = 6</p>
            </li>
            <li>
              <b>Ability Enhancement Course: Environmental Science</b>
              <p>Credits: 4</p>
            </li>
          </ul>
        </li>
      </ul>
    </div>
    <div class="sem-2">
      <h3>Semester - 2</h3>
      <p>Total Credits - 22</p>
      <ul>
        <li>
          <ul>
            <h4>Core Courses:</h4>
            <li>
              <b>BHCS03 - Programming in JAVA with Lab</b>
              <p>Credits: 4 + 2 = 6</p>
            </li>
            <li>
              <b>BHCS04 - Discrete Stuctures with Lab</b>
              <p>Credits: 4 + 2 = 6</p>
            </li>
          </ul>
        </li>
        <li>
          <ul>
            <h4>Other Courses:</h4>
            <li>
              <b>General Elective - 2 with Practical/Tutorial</b>
              <p>Credits: 4/5 + 2/1 = 6</p>
            </li>
            <li>
              <b>Ability Enhancement Course: English/MIL Communication</b>
              <p>Credits: 4</p>
            </li>
          </ul>
        </li>
      </ul>
    </div>
    <div class="sem-3">
      <h3>Semester - 3</h3>
      <p>Total Credits - 28</p>
      <ul>
        <li>
          <ul>
            <h4>Core Courses:</h4>
            <li>
              <b>BHCS05 - Data Structures with Lab</b>
              <p>Credits: 4 + 2 = 6</p>
            </li>
            <li>
              <b>BHCS06 - Operating Systems with Lab</b>
              <p>Credits: 4 + 2 = 6</p>
            </li>
            <li>
              <b>BHCS07 - Computer Networks with Lab</b>
              <p>Credits: 4 + 2 = 6</p>
            </li>
          </ul>
        </li>
        <li>
          <ul>
            <h4>Other Courses:</h4>
            <li>
              <b>Skill Enhancement Course - 1</b>
              <p>Credits: 4</p>
              <ul>
                <li><b>BHCS19A - Web Design and Development</b></li>
                <li><b>BHCS19B - Programming in Python</b></li>
              </ul>
            </li>
            <li>
              <b>General Elective - 3 with Practical/Tutorial</b>
              <p>Credits: 4/5 + 2/1 = 6</p>
            </li>
          </ul>
        </li>
      </ul>
    </div>
    <div class="sem-4">
      <h3>Semester - 4</h3>
      <p>Total Credits - 28</p>
      <ul>
        <li>
          <ul>
            <h4>Core Courses:</h4>
            <li>
              <b>BHCS08 - Design and Analysis of Algorithm with Lab</b>
              <p>Credits: 4 + 2 = 6</p>
            </li>
            <li>
              <b>BHCS09 - Software Engineering with Lab</b>
              <p>Credits: 4 + 2 = 6</p>
            </li>
            <li>
              <b>BHCS10 - Database Management Systems with Lab</b>
              <p>Credits: 4 + 2 = 6</p>
            </li>
          </ul>
        </li>
        <li>
          <ul>
            <h4>Other Courses:</h4>
            <li>
              <b>Skill Enhancement Course - 2 (Choose any one)</b>
              <p>Credits: 4</p>
              <ul>
                <li><b>BHCS20A - Android Programming</b></li>
                <li><b>BHCS20B - Introduction to R Programming</b></li>
              </ul>
            </li>
            <li>
              <b>General Elective - 4 with Practical/Tutorial</b>
              <p>Credits: 4/5 + 2/1 = 6</p>
            </li>
          </ul>
        </li>
      </ul>
    </div>
    <div class="sem-5">
      <h3>Semester - 5</h3>
      <p>Total Credits - 24</p>
      <ul>
        <li>
          <ul>
            <h4>Core Courses:</h4>
            <li>
              <b>BHCS11 - Internet Technologies</b>
              <p>Credits: 4 + 2 = 6</p>
            </li>
            <li>
              <b>BHCS12 - Theory of Computation with Tutorial</b>
              <p>Credits: 4 + 2 = 6</p>
            </li>
          </ul>
        </li>
        <li>
          <ul>
            <h4>Discipline Specific Elective Papers (DSE):</h4>
            <li>
              <b>DSE - 1 (Choose any one)</b>
              <p>Credits: 4 + 2 = 6</p>
              <ul>
                <li><b>BHCS15A - Data Analysis and Visualisation</b></li>
                <li><b>BHCS15B - System Programming</b></li>
                <li><b>BHCS15C - Combinatorial Optimization</b></li>
              </ul>
            </li>
            <li>
              <b>DSE - 2 (Choose any one)</b>
              <p>Credits: 4 + 2 = 6</p>
              <ul>
                <li><b>BHCS16A - Digital Image Processing</b></li>
                <li><b>BHCS17B - Microprocessors</b></li>
              </ul>
            </li>
          </ul>
        </li>
      </ul>
    </div>
    <div class="sem-6">
      <h3>Semester - 6</h3>
      <p>Total Credits - 24</p>
      <ul>
        <li>
          <ul>
            <h4>Core Courses:</h4>
            <li>
              <b>BHCS13 - Artificial Intelligence with Lab</b>
              <p>Credits: 4 + 2 = 6</p>
            </li>
            <li>
              <b>BHCS14 - Computer Graphics with Lab</b>
              <p>Credits: 4 + 2 = 6</p>
            </li>
          </ul>
        </li>
        <li>
          <ul>
            <h4>Discipline Specific Elective Papers (DSE):</h4>
            <li>
              <b>DSE - 1 (Choose any one)</b>
              <p>Credits: 4 + 2 = 6</p>
              <ul>
                <li><b>BHCS17A - Information Security</b></li>
                <li><b>BHCS17B - Data Mining</b></li>
                <li><b>BHCS17C - Advanced Algorithms</b></li>
              </ul>
            </li>
            <li>
              <b>DSE - 2 (Choose any one)</b>
              <p>Credits: 4 + 2 = 6</p>
              <ul>
                <li><b>BHCS18A - Machine Learning</b></li>
                <li><b>BHCS18B - Deep Learning</b></li>
                <li><b>BHCS18C - Unix Network Programming</b></li>
                <li><b>BHCS18D - Project Work/Dissertation</b></li>
              </ul>
            </li>
          </ul>
        </li>
      </ul>
    </div>
  </section>
  <hr>
  <section class="future-possibilities">
    <h2>Future Posibilities</h2>
    <ul>
      <li>
        <ul>
          <h3>Academic Possibilities</h3>
          <li>MSc in Computer Science</li>
          <li>Masters in Computer Applications (MCA)</li>
          <li>Masters in Business Administration</li>
        </ul>
      </li>
      <li>
        <ul>
          <h3>Job Opportunities</h3>
          <li>Software Engineer</li>
          <li>System Analyst</li>
          <li>Cyber Security Manager</li>
          <li>Full-Stack Developer</li>
          <li>Web Developer</li>
          <li>Mobile App Developer</li>
          <li>Database Manager</li>
        </ul>
      </li>
      <li>
        <h3>Entrepreneurship & Startup</h3>
      </li>
    </ul>
  </section>
  <hr />
  <button id="btn">Style This Page</button>
  <footer>
    <p>
      Made by Anshul Verma (19/78065) as a Practical for
      Internal Exam in Course: Information Technology for University of Delhi.
    </p>
  </footer>
</body>
</html>
```
