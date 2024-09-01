# login page 📃
### As you are going to start up with HTML its best practice to start with something basic 
* Start of with a login page with just a heading `(login page)`
* Add some paragraphs or text
* simpily make 2 boxes for the user input and we're done 
```
<!DOCTYPE html>
<html>
 <head>
  <title>Page Title</title>
</head>
  <body>
    <h1 style="color:green;">Login Page</h1>
     <p>enter your <b style="color:green;">username and password</b> in the boxes below</p>
 <input type="text" value="enter your username"/>
  <br></br>
  <input type="password"/>   
    </body>
</html>
```
* **Alright** now lets make something abit more attractive and not something to basic
* lets make a **form ⬇️**
### Basic form 📑
```
<!DOCTYPE html>
<html>
 <head>
  <title>Page Title</title>
</head>
  <form>
  <body style="background-color:powderblue;">
    <h1>Info Form 📑</h1>
    <hr></hr>
     <p>Please fill the Info Correctly in the boxes below</p>
     <p><b>Enter Your Name </p>
     <input style="border:2px DodgerBlue;" type="text" value="ie.name"/>
  <p><b>Select Your Gender</b></p>
  <label>
  <input name="btn" type="radio" value="male"/>Male
</label>
<label>
<input name="btn" type="radio" value="female"/>Female
</label>
  <p><b>Enter Your Age </b></p>
   <input style="border:2px DodgerBlue;" type="date"/>
    <p><b>Enter Your Email</b></p>
    <input style="border:2px DodgerBlue;" type="text" value="@mail.com"/><br></br>
    <p><b>Enter Your Password </b></p>
    <input style="border:2px DodgerBlue;" type="password"/>
    <p><b>Confirm Your Password </b></p>
    <input style="border:2px DodgerBlue;" type="password"/>
    <p>DISCRIPTION <b style =color:green;>(Optional)</br></p>
    <textarea style="border:2px DodgerBlue;"cols="50" rows="5"v>
      Write Something About Your Self
   </textarea><br></br>
   <a herf="https://github.com/mHadi1091">github.com/mHadi1091</a>
    </body>
    </form>
</html>
```
# lets make one with css and html