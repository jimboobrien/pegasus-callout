# Pegasus callout
Use this for "Call To Actions" and special text you want to place at the top below the header or at the bottom before the footer of every page. 

## Usage
How to use in your WordPress site<br>
`[callout button="yes" link="http://example.com" external="yes" color="white" link_text="Learn More" 
background="http://www.wpfreeware.com/themes/html/appstation/img/download_bg.png"]
<p>Get your copy now!Suspendisse vitae bibendum mauris. Nunc iaculis nisl vitae laoreet elementum donec dignissim metus sit.</p>
[/callout]`<br>
Or<br>
`[callout button="yes" link="http://example.com" color="black" external="yes" backgroundcolor="#dedede"]
<h2>Vivamus magna justo, lacinia eget consectetur sed, convallis at tellus. Donec sollicitudin molestie malesuada. Curabitur arcu erat, accumsan id imperdiet et, porttitor at sem. Donec sollicitudin molestie malesuada. Nulla porttitor accumsan tincidunt. Nulla porttitor accumsan tincidunt. Praesent sapien massa, convallis a pellentesque nec, egestas non nisi.</h2>
[/callout]`<br>
Shortcode Attributes: http://pegasustheme.com/pegasus-callout/


## Installation
How to install to your WordPress site

### Simple Instructions 
Go to [Github](https://github.com/Visionquest-Development/pegasus-callout "Github") and click "Clone or download" and make sure it says "Clone with HTTPS" at the top and click "Download Zip" and save it to a folder on your PC. Then, go to WordPress Back-end and go to Plugins -> Add New and then click on "Upload Plugin" and upload the zip file you downloaded from Github.

### Advanced Setup 
#### 1.) Upload via FTP/WordPress Admin<br>
Download zip file from [here](https://github.com/Visionquest-Development/pegasus-callout/archive/master.zip "Github") and on extraction make sure the folder name you extract to is saved as pegasus-callout instead of pegasus-callout-master
Then upload to you server using an FTP program or Use the WordPress Plugin Upload feature in the WordPress Admin.<br>
#### 2.) In the terminal:
###### For https connection use:
`git clone https://github.com/Visionquest-Development/pegasus-callout.git pegasus-callout`

###### For SSH implementation use this command and make sure you have the SSH key setup on both your terminal and github account. You will need to use your passkey for each update.
`git clone git@github.com:Visionquest-Development/pegasus-callout.git pegasus-callout`



## How to update
### Simple Instructions
Use the WordPress Admin or your favorite FTP program to delete the old plugin from the plugins folder. Then follow the Installation instructions again from above.

### Advanced Setup 
If you used the Advanced Setup, all you need to do is `cd /path/where/plugin/exists` && `git pull`.


## How to contribute
If you plan on helping make this plugin better then please follow our guidelines for contributions. We recommend you use a terminal and git clone our repository by using the Advanced Installation Instructions from above. Then, use `git checkout -b new-branch-name` to create your own branch, and rename it to whatever you want by replacing `new-branch-name`. Make your changes and then add and commit them to your branch. Make sure to use `git push -u origin new-branch-name` with the new name when you get done committing your changes to set the upstream for your branch. Then, login to github.com and go to the repo you updated with your new branch and submit a Pull Request. We will review Pull Requests and accept them if it fits with our guidelines and current setup.



