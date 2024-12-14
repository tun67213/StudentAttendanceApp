# StudentAttendanceApp
 
## Description
    This app is meant to provide users with the ability to:
        1. Sign-up for an account with:
            1. an email address
            2. a username
            3. a password (which will be strength checked)
            4. the user's identity, i.e., selecting whether they are a student or a TA/an instructor
            5. a security question selectable from a list of pre-set questions
            6. a place to write the answer for the security question
        2. When the sign up button is pressed, the program must encrypt and save all the data and append it to a text file, and then show a dropdown saying "Account Created", before returning BACK to the login screen.
        3. Once back, when the user hits the button 'LOGIN', if username and/or password is empty, the program must change the background to red, displaying an error saying, "username and/or password is missing". 
        4. Once inside, if the account is a student account, it will show the attendance history for that student. Otherwise, it will show an attendance record for the current date to the instructor/TA.