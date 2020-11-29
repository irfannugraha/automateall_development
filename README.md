# This is Automate All Website Source Code

## This website uses
- CodeIgniter 4 (PHP Framework)
- Bootstrap 4 (CSS Framework)

## Our website is already hosted on heroku, visit the following link
[Automate All](https://automate-all.herokuapp.com) 

## Edit and try this website locally
1. Make sure these are installed 
  - XAMPP/WAMP/LAMP
  - Git
  - Composer
2. Open the Git Bash App, write `cd C:/xampp/htdocs/` and press enter
3. Then, write `git clone https://github.com/alcoffeeocha/automateall` and press enter
4. Check your 'C:/xampp/htdocs/', make sure the 'automateall' folder is there. Open that folder using your code editor
5. You can create your own environment, there is 'env' file in root directory, just rename it with '.env'.
  - Here are some parts that you can change:
    - CI_ENVIRONMENT 
    - app.baseURL
    - DATABASE
    - and dont forget to save the file!
6. Open your XAMPP Control Panel, start Apache and MySQL modules
7. Click the Admin button in MySQL module, this will take you to phpMyAdmin. In phpMyAdmin Create a database called automateall_db (or with database name in .env)
and just skip the table creation
8. Back to your Git Bash. write `php spark migrate` and press enter. If the process is complete, write `php spark db:seed messages` and press enter
write `php spark db:seed news` and press enter, last, write `php spark db:seed product` and press enter.
9. You can run the application by executing `php spark serve` in Git Bash. Open your browser, and browse 'localhost:8080'

For more, you can visit CodeIgniter 4 Documentation.


Copyright © 2020 Automate All.


