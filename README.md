# web-design-week-4-assignment
login 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Form</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h2>Login Form</h2>
    <form id="loginForm">
        <!-- Email Field -->
        <label for="loginEmail">Email:</label>
        <input type="email" id="loginEmail" name="loginEmail" required>
        <span class="error" id="loginEmailError"></span><br><br>

        <!-- Password Field -->
        <label for="loginPassword">Password:</label>
        <input type="password" id="loginPassword" name="loginPassword" required>
        <span class="error" id="loginPasswordError"></span><br><br>

        <!-- Login Button -->
        <button type="submit">Login</button>
    </form>

    <script src="script.js"></script>
</body>
</html>
REGISTRATION FORM
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration Form</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h2>Registration Form</h2>
    <form id="registrationForm">
        <!-- Name Field -->
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
        <span class="error" id="nameError"></span><br><br>

        <!-- Email Field -->
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        <span class="error" id="emailError"></span><br><br>

        <!-- Password Field -->
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" required>
        <span class="error" id="passwordError"></span><br><br>

        <!-- Confirm Password Field -->
        <label for="confirmPassword">Confirm Password:</label>
        <input type="password" id="confirmPassword" name="confirmPassword" required>
        <span class="error" id="confirmPasswordError"></span><br><br>

        <!-- Age Field -->
        <label for="age">Age:</label>
        <input type="number" id="age" name="age" required>
        <span class="error" id="ageError"></span><br><br>

        <!-- Gender Field -->
        <label>Gender:</label><br>
        <input type="radio" id="male" name="gender" value="male" required>
        <label for="male">Male</label><br>
        <input type="radio" id="female" name="gender" value="female" required>
        <label for="female">Female</label><br>
        
        <br>
        <br>

        <!-- Country Field -->
        <label for="country">Country:</label>
        <select id="country" name="country" required>
            <option value="ALGERIA">ALGERIA</option>
            <option value="ANGOLA">ANGOLA</option>
            <option value="BENIN">BENIN</option>
            <option value="BOTSWANA">BOTSWANA</option>
            <option value="BURKINA FASO">BURKINA FASO</option>
            <option value="BURUNDI">BURUNDI</option>
            <option value="CABO VERDE">CABO VERDE</option>
            <option value="CAMEROON">CAMEROON</option>
            <option value="CENTRAL AFRICAN REPUBLIC">CENTRAL AFRICAN REPUBLIC</option>
            <option value="CHAD">CHAD</option>
            <option value="COMOROS">COMOROS</option>
            <option value="CÔTE D'IVOIRE">CÔTE D'IVOIRE</option>
            <option value="DEMOCRATIC REPUBLIC OF THE CONGO">DEMOCRATIC REPUBLIC OF THE CONGO</option>
            <option value="DJIBOUTI">DJIBOUTI</option>
            <option value="EGYPT">EGYPT</option>
            <option value="EQUATORIAL GUINEA">EQUATORIAL GUINEA</option>
            <option value="ERITREA">ERITREA</option>
            <option value="ESWATINI">ESWATINI</option>
            <option value="ETHIOPIA">ETHIOPIA</option>
            <option value="GABON">GABON</option>
            <option value="GAMBIA">GAMBIA</option>
            <option value="GHANA">GHANA</option>
            <option value="GUINEA">GUINEA</option>
            <option value="GUINEA-BISSAU">GUINEA-BISSAU</option>
            <option value="KENYA">KENYA</option>
            <option value="LESOTHO">LESOTHO</option>
            <option value="LIBERIA">LIBERIA</option>
            <option value="LIBYA">LIBYA</option>
            <option value="MADAGASCAR">MADAGASCAR</option>
            <option value="MALAWI">MALAWI</option>
            <option value="MALI">MALI</option>
            <option value="MAURITANIA">MAURITANIA</option>
            <option value="MAURITIUS">MAURITIUS</option>
            <option value="MOROCCO">MOROCCO</option>
            <option value="MOZAMBIQUE">MOZAMBIQUE</option>
            <option value="NAMIBIA">NAMIBIA</option>
            <option value="NIGER">NIGER</option>
            <option value="NIGERIA">NIGERIA</option>
            <option value="RWANDA">RWANDA</option>
            <option value="SÃO TOMÉ AND PRÍNCIPE">SÃO TOMÉ AND PRÍNCIPE</option>
            <option value="SENEGAL">SENEGAL</option>
            <option value="Seychelles">SEYCHELLES</option>
            <option value="Sierra Leone">SIERRA LEONE</option>
            <option value="SOMALIA">SOMALIA</option>
            <option value="SOUTH AFRICA">SOUTH AFRICA</option>
            <option value="SOUTH SUDAN">SOUTH SUDAN</option>
            <option value="SUDAN">SUDAN</option>
            <option value="TANZANIA">TANZANIA</option>
            <option value="TOGO">TOGO</option>
            <option value="TUNISIA">TUNISIA</option>
            <option value="UGANDA">UGANDA</option>
            <option value="ZAMBIA">ZAMBIA</option>
            <option value="ZIMBABWE">ZIMBABWE</option>
        </select>
        <span class="error" id="countryError"></span><br><br>

        <!-- Terms and Conditions Checkbox -->
        <label>
            <input type="checkbox" id="terms" name="terms" required>
            I accept the terms and conditions
        </label>
        <span class="error" id="termsError"></span><br><br>

        <!-- Submit Button -->
        <button type="submit">Submit</button>
    </form>

    <script src="script.js"></script>
</body>
</html>
CSS
/* style.css */
body {
    font-family: Arial, sans-serif;
    margin: 20px;
}

h2 {
    text-align: center;
}

form {
    max-width: 400px;
    margin: 0 auto;
    padding: 20px;
    border: 1px solid #ccc;
    border-radius: 10px;
}

label {
    display: block;
    margin: 5px 0;
}

input, select {
    width: 100%;
    padding: 8px;
    margin: 5px 0;
    box-sizing: border-box;
}

button {
    width: 100%;
    padding: 10px;
    background-color: #4CAF50;
    color: white;
    border: none;
    cursor: pointer;
    margin-top: 10px;
}

button:hover {
    background-color: black;
JAVASCRIPT
// Validation for Registration Form
document.getElementById('registrationForm').addEventListener('submit', function(event) {
    event.preventDefault(); // Prevent form submission until validation is complete

    // Clear previous error messages
    clearErrors();

    // Get form data
    const name = document.getElementById('name').value;
    const email = document.getElementById('email').value;
    const password = document.getElementById('password').value;
    const confirmPassword = document.getElementById('confirmPassword').value;
    const age = document.getElementById('age').value;
    const gender = document.querySelector('input[name="gender"]:checked');
    const country = document.getElementById('country').value;
    const terms = document.getElementById('terms').checked;

    let isValid = true;

    // Name validation
    if (!name) {
        displayError('nameError', 'Name is required');
        isValid = false;
    }

    // Email validation
    const emailRegex = /^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$/;
    if (!email || !emailRegex.test(email)) {
        displayError('emailError', 'Please enter a valid email address');
        isValid = false;
    }

    // Password validation
    if (!password || password.length < 8) {
        displayError('passwordError', 'Password must be at least 8 characters long');
        isValid = false;
    }

    // Confirm Password validation
    if (password !== confirmPassword) {
        displayError('confirmPasswordError', 'Passwords do not match');
        isValid = false;
    }

    // Age validation
    if (!age || age < 18 || age > 100) {
        displayError('ageError', 'Please enter a valid age (18-100)');
        isValid = false;
    }

    // Gender validation
    if (!gender) {
        displayError('genderError', 'Please select your gender');
        isValid = false;
    }

    // Country validation
    if (!country) {
        displayError('countryError', 'Please select your country');
        isValid = false;
    }

    // Terms and conditions validation
    if (!terms) {
        displayError('termsError', 'You must accept the terms and conditions');
        isValid = false;
    }

    // If all fields are valid, submit the form
    if (isValid) {
        alert('Registration successful!');
        document.getElementById('registrationForm').submit();
    }
});

// Validation for Login Form
document.getElementById('loginForm').addEventListener('submit', function(event) {
    event.preventDefault(); // Prevent form submission until validation is complete

    // Clear previous error messages
    clearErrors();

    // Get form data
    const loginEmail = document.getElementById('loginEmail').value;
    const loginPassword = document.getElementById('loginPassword').value;

    let isValid = true;

    // Email validation
    if (!loginEmail) {
        displayError('loginEmailError', 'Email is required');
        isValid = false;
    }

    // Password validation
    if (!loginPassword) {
        displayError('loginPasswordError', 'Password is required');
        isValid = false;
    }

    // If all fields are valid, submit the form
    if (isValid) {
        alert('Login successful!');
        document.getElementById('loginForm').submit();
    }
});

// Function to display error messages
function displayError(id, message) {
    document.getElementById(id).innerText = message;
}

// Function to clear error messages
function clearErrors() {
    const errorElements = document.querySelectorAll('.error');
    errorElements.forEach(function(element) {
        element.innerText = '';
    });
}
