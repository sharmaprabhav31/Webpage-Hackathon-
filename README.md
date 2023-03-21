# Webpage-Hackathon-
  
<meta name="viewport" content="width=device-width, initial-scale=1">  
<style>  
body{  
  font-family: Calibri, Helvetica, sans-serif;  
  background-color: pink;  
}  <html>  
<head>
.container {  
    padding: 50px;  
  background-color: lightblue;  
}  
  
input[type=text], input[type=password], textarea {  
  width: 100%;  
  padding: 15px;  
  margin: 5px 0 22px 0;  
  display: inline-block;  
  border: none;  
  background: #f1f1f1;  
}  
input[type=text]:focus, input[type=password]:focus {  
  background-color: green;  
  outline: none;  
}
 div {  
            padding: 10px 0;  
         }  
hr {  
  border: 1px solid #f1f1f1;  
  margin-bottom: 25px;  
}  
.registerbtn {  
  background-color: #4CAF50;  
  color: white;  
  padding: 16px 20px;  
  margin: 8px 0;  
  border: none;  
  cursor: pointer;  
  width: 100%;  
  opacity: 0.9;  
}  
.registerbtn:hover {  
  opacity: 1;  
}  
</style>  
</head>  
<body>  
<form>  
  <div class="container">  
  <center>  <h1> CITIZEN REGISTRATION PORTAL</h1> </center>  
  <hr>  
  <label> Firstname </label>   
<input type="text" name="firstname" placeholder= "Firstname" size="15" required />   
<label> Middlename: </label>   
<input type="text" name="middlename" placeholder="Middlename" size="15" required />   
<label> Lastname: </label>    
<input type="text" name="lastname" placeholder="Lastname" size="15"required />   
<div>  
<label>   
DISEASE :  
</label>   
  
<select>  
<option value="Course">SELECT DISEASE</option>  
<option value="CANCER">CANCER</option>  
<option value="TUBERCULOSIS">TUBERCULOSIS</option>  
<option value="DIABATES">DIABETES</option>  
<option value="ASTHAMA">ASTHAMA</option>  
<option value="MIGRAINE">MIGRAINE</option>  
<option value="BLOOD PRESSUR">BLOOD PRESSURE</option>  
</select>  
</div>  
<div>  
<label>   
Gender :  
</label><br>  
<input type="radio" value="Male" name="gender" checked > Male   
<input type="radio" value="Female" name="gender"> Female   
<input type="radio" value="Other" name="gender"> Other  
  
</div>  
<label>   
Phone :  
</label>  
<input type="text" name="country code" placeholder="Country Code"  value="+91" size="2"/>   
<input type="text" name="phone" placeholder="phone no." size="10"/ required>   
Current Address :  
<textarea cols="80" rows="5" placeholder="Current Address" value="address" required>  
</textarea>  
 <label for="AADHAR NUMBER"><b>AADHAR NUMBER</b></label>  
 <input type="text" placeholder="Enter aadhar number" name="number" required>  
  
    <label for="OTP"><b>OTP</b></label>  
    <input type="OTP" placeholder="Enter OTP" name="OTP" required>  
  
    
    <button type="submit" class="registerbtn">Register</button>    
</form>  


    </div>
  </div>
  
</body>  
</html>
