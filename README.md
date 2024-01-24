# leninkumar
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Survey Form</title>
  <style>
    body {
      background-color: #333;
      color: #fff;
      font-family: Arial, sans-serif;
    }
 form {
      max-width: 400px;
      margin: 50px auto;
    }
  label {
      display: block;
      margin-bottom: 8px;
    }
input, select {
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
      box-sizing: border-box;
    }
 input[type="submit"] {
      background-color: #4CAF50;
      color: #fff;
      cursor: pointer;
    }
 input[type="submit"]:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>

  <form id="surveyForm">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required>

  <label for="age">Age:</label>
    <input type="number" id="age" name="age" required>

   <label for="gender">Gender:</label>
    <select id="gender" name="gender" required>
      <option value="male">Male</option>
      <option value="female">Female</option>
   <option value="other">Other</option>
  </select>

   <label for="qualification">Qualification:</label>
   <input type="text" id="qualification" name="qualification" required>

   <label for="occupation">Occupation:</label>
   <input type="text" id="occupation" name="occupation" required>

   <label for="address">Address:</label>
   <textarea id="address" name="address" rows="4" required></textarea>

   <label for="feedback">Feedback:</label>
  <textarea id="feedback" name="feedback" rows="4" required></textarea>
  <input type="submit" value="Submit">
  </form>

  <script>
    document.getElementById("surveyForm").addEventListener("submit", function(event) {
      event.preventDefault();
    });
  </script>

</body>
</html>
 ⁠
