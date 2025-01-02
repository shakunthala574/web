<html><head> 
  <meta charset="UTF-8"> 
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
  <title>Student Information Form</title> 
  <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #808080;
        }
        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
        form {
            width: 60%;
            margin: 20px auto;
            background-color: white;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        table {
            width: 100%;
            margin-bottom: 20px;
        }
        td {
            padding: 10px;
            text-align: left;
        }
        input[type="text"], input[type="number"], input[type="email"] {
            width: 100%;
            padding: 8px;
            margin: 5px 0;
            border: 1px solid #ddd;
            border-radius: 4px;
        }
        input[type="button"], input[type="submit"] {
            padding: 10px 20px;
            margin: 10px 5px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        input[type="reset"] {
            background-color: #f44336;
            color: white;
        }
        input[type="submit"] {
            background-color: #4CAF50;
            color: white;
        }
        input[type="reset"]:hover, input[type="submit"]:hover {
            opacity: 0.8;
        }
    </style> 
 </head> 
 <body> 
  <header> 
   <h1>Student Information Form</h1> 
  </header> 
  <form id="studentForm"> 
   <table> 
    <tbody>
     <tr> 
      <td><label for="name">Name:</label></td> 
      <td><input type="text" id="name" name="name" required=""></td> 
     </tr> 
     <tr> 
      <td><label for="phone">Phone Number:</label></td> 
      <td><input type="number" id="phone" name="phone" required=""></td> 
     </tr> 
     <tr> 
      <td><label for="email">Email:</label></td> 
      <td><input type="email" id="email" name="email" required=""></td> 
     </tr> 
     <tr> 
      <td><label for="address1">State 1:</label></td> 
      <td><input type="text" id="address1" name="address1" required=""></td> 
     </tr> 
     <tr> 
      <td><label for="address2">district Line 2:</label></td> 
      <td><input type="text" id="address2" name="address2"></td> 
     </tr> 
     <tr> 
      <td><label for="address3">Address Line 3:</label></td> 
      <td><input type="text" id="address3" name="address3"></td> 
     </tr> 
     <tr> 
      <td><label for="city">City:</label></td> 
      <td><input type="text" id="city" name="city" required=""></td> 
     </tr> 
     <tr> 
      <td><label for="pin">Pin Code:</label></td> 
      <td><input type="number" id="pin" name="pin" required=""></td> 
     </tr> 
     <tr> 
      <td><label for="m1">1st year maths 1:</label></td> 
      <td><input type="number" id="m1" name="m1" required=""></td> 
     </tr> 
     <tr> 
      <td><label for="m2">2nd year March 2:</label></td> 
      <td><input type="number" id="m2" name="m2"></td> 
     </tr> 
     <tr> 
      <td><label for="m3">3rd year march 3:</label></td> 
      <td><input type="number" id="m3" name="m3"></td> 
     </tr> 
    </tbody>
   </table> 
   <input type="reset" value="Reset"> 
   <input type="submit" value="Submit"> 
  </form> 
  <script>
    // Handle form submission
    document.getElementById("studentForm").addEventListener("submit", function(event){
        event.preventDefault();
        alert("Form Submitted Successfully!");
        // You can also add more code here to send the form data to a server if needed
    });
</script> 
 
</body></html>
