Download Link: https://assignmentchef.com/product/solved-swe645-assignment-2
<br>
Your second assignment involves creating a Dynamic Web Project using your favorite IDE such as, Eclipse EE. The project includes a Student Survey form (HTML) and an external cascading stylesheet (CSS). The requirements of the Student Survey form and the stylesheet are described below. Make sure you can deploy and access your application on your local Tomcat instance, prior to deploying the war file on the Tomcat server running on Amazon EC2 instance in AWS cloud. Please add the link of your application to your website on Amazon S3, that you created in the previous assignment.  Also, provide URL of your homepage as well as of the application deployed on EC2 in readme file as part of your HW submission on the class blackboard.

<ul>

 <li>Use EC2 Amazon Machine Image (AMI) labeled “Tomcat Certified by Bitnami” found under AWS Marketplace to launch your EC2 instance.

  <ul>

   <li>Provision a free tier eligible Amazon EC2 instance using an Amazon Machine Image (AMI) that may already have Tomcat configured.</li>

   <li>For example, once you are on EC2 Console, click Launch Instance link. For the AMI, search for key word “Tomcat” in <strong>AWS Marketplace</strong> and select the machine image labeled something like “Tomcat Certified by Bitnami” – the one labelled as free tier eligible.</li>

  </ul></li>

 <li>Develop a student survey form to allow a user to enter the survey data. In particular, the student survey form contains the following:

  <ul>

   <li>Text boxes for first name, last name, street address, city, state, zip, telephone number, e-mail, and date of survey, which are required fields. o Checkboxes that allow prospective students to indicate what they liked most about the campus. The checkboxes should include: students, location, campus, atmosphere, dorm rooms, and sports. o Radio buttons that allow the prospective students to indicate how they became interested in the university. Options should include: friends, television, Internet, and other.</li>

   <li>A dropdown list of options for the user to select the likelihood of him/her recommending this school to other prospective students. The three options of the dropdown list are: Very Likely, Likely, Unlikely.</li>

   <li>An additional text box called Raffle. The user will be asked to enter at least ten comma separated numbers ranging from 1 through100 in the Raffle field. This information will be used to announce whether the student wins a free movie ticket.</li>

   <li>A text area for additional comments, and o Submit and cancel buttons.</li>

  </ul></li>

 <li>In addition, create an external style sheet to specify the following requirements for your page:

  <ul>

   <li>Use an external Cascading Style Sheet (CSS) to customize formatting and presentation of your web page. The CSS could be used for fonts, colors, borders, background etc. You are free to be as much creative as you can. At the very least, the style sheet should include a rule that displays h1 elements in blue color, which could be used to specify the heading of the survey page. Also, the heading at the top of the Student Survey page should be inside a rectangular box using blue solid border of 5px width. Also include a border around your Survey form. The labels of different fields on the form should be any color of your choice except black. Also, the body of the window rendering your page should have a light gray (or a color of your choice) background.</li>

  </ul></li>

</ul>

<strong>Submission </strong>

The submission for this assignment should be through the blackboard website. I expect a zipped package containing the source files, war file, and any additional packages, scripts, or files that you used. I also require a readme file which contains installation and set up instructions so that the TA and myself can deploy and run the assignment. I also expect AWS URL of your homepage as part of readme file. Submit all source, and war file, files necessary to run the application and the installation and execution instructions. Please put all of the files in a zip file. If you submit an assignment late (i.e., not submitted on due date) the late penalty will apply.

NOTE: A late assignment carries a 10% late penalty for each week it is late. Assignments are NOT accepted after being 2 weeks late. Make sure your name is on every programming artifact so we know who it belongs to. For every source file, please include comments at the top of the program describing what the program does. This only needs to be 1 or 2 sentences. Be sure to test access and functionality to your submission before the due date.

<strong>Grading</strong>:

The following areas will be used in the basic grading of these projects:

<ul>

 <li>Does system meet the functional requirements: 85 points</li>

 <li>Does the assignment run without errors: 13 points</li>

 <li>Comments: 2 points <strong>Instant Point Deductions: </strong></li>

</ul>

I reserve the right to deduct points instantly for the following reasons:

<ul>

 <li>The source, or binary, files are not included in the package.</li>

 <li>The readme file is not included in the package.</li>

 <li>The program doesn’t run due to errors in the code.</li>

 <li>I can’t figure out how to use the assignment, and instructions are left out.</li>

</ul>