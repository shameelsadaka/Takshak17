# Takshak Website

# Getting started
- Move to your webserver directory
```
cd /var/www/html - for Linux
```
```
cd C:\wamp64\www\ - for windows running wamp
```
cd  /Users/<username>/Sites/ -if you are using user level directory
```
- Clone the repository
```
git clone https://github.com/ashwinkjoseph/Takshak17.git
```
- Start your Apache and MySQL servers
```
Navigate to `http://localhost/Takshak17/public/

Folder Structure:
    This Project is built according to the MVC Structure
    ~/app contains all php files.
    ~/app/controllers contains all controllers
    ~/app/core contains the main routing and controller files
    ~/app/models contains all the database handling files
    ~/app/views contains all the views to be renderes
    ~/public contains all css, js and images

Current Contribution Requirement:
    ~/public/ has a cloud.html, the webpage should be edited such that the 
        1. Title zooms in while fading in slowly from the center
        2. The title (contained in ~/public/images/title.png(or)title.psd) should be further edited to match the setting of the page
        3. An opensource background music is required for the page (Contact maintainer for information on what kind at ashwinkjoseph@gmail.com)
        4. The transitions od the title and the covering clouds should be made smoother and from the center