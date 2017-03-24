# Start_build

My monster for speed in web-development.

## Getting Started


On your computer must be installed: Node.js, npm, bower.

Steps:
git clone https://github.com/verino/start_build.git

Rename the folder start_build, give it a new name for the current project.

In the folder "src" create the folder "libs": mkdir libs.

Remove folder ".git"

Git Bash: git init, git add ., git commit -a -m "commit", git status.

View the file bower.json and remove unnecessary dependencies and then install the necessary plug-ins using the command
```
bower i
```
Install the gulp modules specified in the gulpfile.js using the command
```
npm i
```
The following gulp commands:
```
gulp build
```

- mandatory command, generates the dist directory

```
gulp
```

- launches watch.



And the next steps, concerning the features of the new project:
<ol>
<li>Whether the file mail.php is necessary, if is not present I delete it from folder src, and as I delete a command from gulp.js concerning this file.</li>
<li>Index.html - to leave the necessary components and swap, components.scss- the same,
libs.scss-same,libs.js and custom.js - same</li>
<li>
Some libraries that connect bower (the paths are written in libs.scss) require changes in the style files of .css extensions to .scss (For example: nouislider.min.scss).</li>
<li>css/variables-projects.scss based variables-helpers.scss</li>
<li>css/mixins-projects.scss</li>
<li>grid.scss</li>
<li>icons.scss</li>
<li>btnstyle.scss</li>
<li>author.scss</li>
<li>Pictures, fonts, favicons</li>
</ol>





 
