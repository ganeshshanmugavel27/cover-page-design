# cover-page-design
AIM:
To design a static web site for a book cover page.

DESIGN STEPS:
Step 1:
Clone the github repository and create a django admin interface

Step 2:
Write HTML and CSS for designing book cover page and execute them .

Step 3:
Validate the HTML and CSS code.

Step 4:
Publish the website in the given URL.
##code:
cover.html:

<!DOCTYPE html>
<html lang="en">
    <head>
        <title> Easy way to learn coding</title>
        <style>
        h1{
           color:white;
        }
         .bookpage{
             width: 400px;
             height: 650px;
             background-color: black;
             background-position: center;
             margin-left: auto;
             margin-right: auto ;
             padding: 20px;
             background-image: url("navy\ blue.jpg");
             background-size: cover;
             background-repeat: no-repeat;

         }
         .toptext{
             color:white;
             padding-left: 10px;
             font-size: 14px;
             font-family: Arial, Helvetica, sans-serif;

         }
         .tophr{
             color:#e36f2f;
              width: 180px;
         }
         hr{
             color:#e36f2f;

         }
         .booktitle{
             font-family: Arial, Helvetica, sans-serif;
             padding: 10px 10px 0px 10px;
             display: flex;
            align-items: center;
            justify-content: center;
  margin-right: 10px;
  margin-left: 10px;
  font-size: 20px;
         }
         .author{
             color:white;
             font-family: Arial, Helvetica, sans-serif;
             display: inline;
             font-size: 24px;
             position:relative;
             line-height: 20px;


         }
         .sub-text {
             color:white;
             font-family: Arial, Helvetica, sans-serif;
             display: flex;
             line-height: 5px;

  margin-right: 10px;
  margin-left: 10px;

  font-size: 14px;
  }

.footer {
  color:orange;
  padding-top: 180px;
}
.image {
    color:white;
             font-family: Arial, Helvetica, sans-serif;
 font-size: 22px;
  margin-right: 20px;
}
.bottomhr {
    color:#e36f2f;
              width: 400px;

}
img {
    width: 90px;
    height: 100px;
    margin-right: 20px;
    vertical-align: bottom;
}
.edition {
    color:#e36f2f;
             font-family: Arial, Helvetica, sans-serif;
 font-size: 22px;
 line-height:bottom;

}


        </style>
        </head>
            <body>
                <div class="bookpage">

                    <div class="toptext">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;BEGINNER FRIENDLY</div>
                    <div class="tophr"><hr></div>
               <div class="booktitle"><h1>EASY WAY TO LEARN CODING</h1></div>
               <h3 class="sub-text">Learn python,html,css,javascript,C++ in 1 second</h3>
                    <h3 class="sub-text">written by Dr. Ganesh</h3>
                    <div class="footer">
                        <h2 class="edition">&nbsp;&nbsp;Seventh
Edition&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <img src="ganesh.jpg" alt="Author"></h2>

                        <div class="bottomhr"><hr></div>
                    <div class="author"><h3>&nbsp;&nbsp;Ganesh &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</h3></div>

                </div>
                </div>

            </body>


</html>

## Output:
![cover](https://github.com/ganeshshanmugavel27/cover-page-design/assets/122046208/5a650e9f-20e1-4516-9864-17dc9fe08ae9)
![dd1](https://github.com/ganeshshanmugavel27/cover-page-design/assets/122046208/7ea4438a-9938-48d9-959b-034b060308ce)


## Result:
program excuecuted succeessfully
