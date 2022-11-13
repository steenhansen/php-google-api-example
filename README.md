



This code does not work anymore. And [https://google-api-example.herokuapp.com]() has been terminated.

When this program was first developed, websites did not need to go through an approval process to grant read/write access to password protected Google Docs and sheets. An updating Heroku server caused the Google credentials to be invalidated.

Basically, a PHP site used to use a Google spreadsheet to authorize who could log into a PHP program, and what system rights the user has access to.

For instance, steenhansen1942@gmail.com, can log in and view general information. He can also view the 'Docs Manual' whereas test@gmail.com cannot.

The PHP program could change the values in the Google spreadsheet, so as to delete or change a user's name. But the PHP program would never know any passwords.

## Google API calls Example in PHP:


## Access live example
Automatically sign in with 'guest_account' of test@gmail.com   
[https://google-api-example.herokuapp.com/guestSignIn.php](https://google-api-example.herokuapp.com/guestSignIn.php)

Explanations and links to Google doc and sheet used    
[https://google-api-example.herokuapp.com/index.html](https://google-api-example.herokuapp.com/index.html)

Sign in with a "real" Google account that exists in the Google sheet of users       
[https://google-api-example.herokuapp.com/login.php](https://google-api-example.herokuapp.com/login.php)
   
Sign in via URL       
[https://google-api-example.herokuapp.com/signInFromGoogle.php?gmail=test@gmail.com](https://google-api-example.herokuapp.com/signInFromGoogle.php?gmail=test@gmail.com)


The locked but visible Google sheet https://docs.google.com/spreadsheets/d/1vhce-ziBi6wneqJrxd7Zhyqth8ZLHMJHot1wxgK_T7k/edit#gid=0 that is read and written to.

![visual explanation](https://github.com/steenhansen/php-google-api-example/blob/master/google-api.png)
## Information
Sheet/Document/Email/Authorization Classes

    php-google-api-example/Google_Api/


To install composer libraries
    
    php-google-api-example/ composer install


To enable Google credentials

    Copy google-sample files to google-account directory
    

To test
    
    php-google-api-example/  php tests/call_tests.php   

