# swe642-frontend-website
Front-end website developed using HTML5, CSS, and Bootstrap for SWE 642. Includes a personal homepage and a Computer Science department information site with a student survey form. Hosted as a static website on AWS S3.

---------------------------------------------------
Purpose
---------------------------------------------------
This assignment was completed to gain hands-on experience with HTML5, CSS, and the Bootstrap framework. 
The deliverables include:
1. A personal homepage (Part 1).
2. A Computer Science Department information page (Part 2).
3. A CS Department Survey form integrated with Bootstrap and GMU color scheme.

---------------------------------------------------
Project Structure
---------------------------------------------------
/index.html        -> My personal homepage (Part 1).
/css/profile.css   -> Custom stylesheet for homepage.
/csdept.html       -> CS Department information page (Part 2).
/css/csdept.css    -> Custom stylesheet for CS Dept and Survey pages.
/survey.html       -> CS Department survey form page.
images/            -> Contains my profile photo and hero background.
websiteLink.txt    -> Contains AWS S3 public URL for hosted site.

---------------------------------------------------
Part 1: Homepage
---------------------------------------------------
- Built using W3.CSS template.
- Contains my profile photo, About Me section, Skills (badges), Projects, and Contact information.
- Navbar links to About, Projects, Contact, and CS Department page.
- Footer includes © 2025 with my name.

---------------------------------------------------
Part 2: CS Department Info + Survey
---------------------------------------------------
- CS Department information page includes:
  * A description of the department.
  * List of MS degree programs.
  * Tables with required courses for each MS program.
  * A link to the survey page.
- Survey page includes:
  * Input fields: Full Name, Email, Address, City, State, Zip, Phone, LinkedIn URL, Date.
  * Datalist for High School Graduation Month and Number input for Year.
  * Checkboxes for campus likes.
  * Radio buttons for "How you became interested in the university".
  * Dropdown for likelihood of recommending the school.
  * Text area for comments.
  * Submit button styled with GMU colors.
  * Required fields visually marked with an asterisk.
  * Page styled with GMU Green (#006633) and GMU Yellow (#FFCC33).

---------------------------------------------------
Styling and Accessibility
---------------------------------------------------
- Used Bootstrap 5 framework for responsive layout.
- Custom CSS (csdept.css) with GMU brand colors as CSS variables.
- Required labels marked with `::after` pseudo-class.
- Accessible with ARIA labels and proper form attributes.
- Autocomplete enabled on form.

---------------------------------------------------
Hosting
---------------------------------------------------
The website is hosted on AWS S3 as a static site.
URL: http://sanjanaassignment1.s3-website-us-east-1.amazonaws.com

---------------------------------------------------
Notes
---------------------------------------------------
- Part 1 (homepage) is the landing page of the S3 bucket.
- Part 1 links to Part 2 (CS Dept page).
- Part 2 links to the Survey page.
- Survey page includes a link back to CS Dept page.
- All requirements specified in the assignment instructions have been implemented.

---------------------------------------------------
End of README
---------------------------------------------------
