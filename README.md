# WP-Responsive-Slideshows

WP Responsive Slideshows Plugin for Adding Multiple Resposive Slideshow into WP Sites.

-----------------------

List of requirements for the Final project submission:

### Features : 
* Adding / Removing Images and Videos in WP-ADMIN Support
* Adding Images By URL in WP-ADMIN Support
* WP Tinymce Adding/Inserting Slideshow Shortcode Button Support
* Support for Editing Slideshow from Tinymce Shortcode Button Popup
* Responsive Slideshow
* Slideshow Touch Events Support

-------

### REMOVE SENSITIVE INFORMATION FROM CODE (RESET YOUR REPO)

If you had any passwords in your code, you should remove them and place them in your .env file. For example in your .env file you have a MONGOLAB_URI variable
    
    MONGOLAB_URI=mongodb://.....
    
You can access this variable in your code with the statement (when using foreman start)

    process.env.MONGOLAB_URI
    
Your .env file should be included in your .gitignore file

### RESET THE REPO

Once you have moved sensitive passwords out of your repo. You can reset your repo by removing the .git directory and reinitalizing the repo. In your code directory in terminal, remove the .git directory

**You only need to do this if you have any passwords in your code (outside your .env file)**

**THIS WILL REMOVE ALL COMMIT HISTORY FROM YOUR REPO**

    rm -rf .git
    
Now you can re-initialize the repo knowing that your passwords will not be in the history. In your code directory in terminal.

    git init
    git add .
    git commit -am "reinit"

Now add in the remote paths to PUSH to Heroku and Github, you must replace with your REPO information

    git remote add heroku git@heroku.com:YOUR-HEROKU-APP.git
    git remote add github git@github.com:GITHUB_USERNAME/GIT-REPO.git
    


    


### When finished - push your code repository to Github

--force command will push

    git push --force github
