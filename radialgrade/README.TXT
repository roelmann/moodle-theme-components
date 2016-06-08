This plugin has been tested in More which uses LESS on the fly, but can be used in other themes (such as CLEAN) 
by using GRUNT to process the LESS. See https://docs.moodle.org/dev/Grunt

Copy the radialgrade.php file into your layouts folder - if your theme inherits all its layouts you will need to
add the layout folder and relevant layout file (e.g. courses.php or columns3.php) to your theme as you will need to edit
the relevant layout file to display the radial grade.

Copy the LESS section of the file into the theme LESS file, or into a new file that can be process using GRUNT if your
theme does not already have one.

Add <?php include ('radialgrade.php');?> to your layout file where you want the radialgrade to appear.

@credits
https://moodle.org/mod/forum/discuss.php?d=314373#p1319920 - Jerome Di Pietro, 
for first making this into a block and posting it in the Moodle forums
(I simply converted his work into a 'component' usable within Theme code)
That link also provides upstream credit for the work originally done to create
the radial block effect by @andsens
