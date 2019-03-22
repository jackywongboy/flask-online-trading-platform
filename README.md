# flask-online-trading-platform-windows
This file is for winodws based platform. <br><br>
Using python 3.7 and Flask 1.0.2 and Mysql Database.
<br><hr>
If you are Linux users, you may use this version.<a href="https://github.com/jackywongboy/flask-online-trading-platform-Linux" >Link</a><br>
<hr>
<h1><b>How to run the app</b></h1><br>
<p>you need a local host and database, so download XAMPP</p>
<a href="https://www.apachefriends.org/download.html" target="_blank">Download Link</a>
<p>Please follow the instruction to install Xampp</p>
<p>After you install, please try to start the local host.</p>
<p>You may have problem on starting the server. Please run XAMPP in admin mode by right click "run as admin"</p>
<p>Remember that you need to start the "MySql server" and "Apache"</p>
<p>Please makesure that XAMPP can support Python code, you may :</p>
<ol>
    <li>Click the Config button on Apache</li><p>Choose "httpd.conf"</p>
    <li>Find "AddHandler cgi-script .cgi .pl .asp"</li><p>Add ".py" after .asp</p>
    <li>Ater that, restart XAMPP </li>
</ol>
<p>you may then able to start, go to "localhost/phpmyadmin/"</p>
<hr>
<p>create a new data base name : "oceanshopdb"</p>
<p>import my SQL file into Mysql</p>
<p>If it success, you may see 5 column in oceanshopdb</p>
<hr>
<p>Install python3 and pip</p>
<p>Use pip install all the feathers that are need, all feathers are on the top in "app.py"</p>
<p>After import all the needed feathers, you may run the app</p>
<p>Remember to run CMD as admin before update and install tools</p>
<hr>
<h1>Windows import Flask has some annoying error</h1>
<h3>if you success import Flask but cannot start the server because its stuck at Debug mode and did not pop up a href</h3>
<p>Please Re-install Python everything, including Script</p>
<p>After that this bug may solve</p>
<h3>Unable to import Flask-mysqldb by error "Microsoft Visual C++ 14.0 is required."</h3>
<p>No need to download the Microsoft Visual C++ 14.0.</p>
<p>Please go to link of this project file.</p>
<p>run command : "pip install mysqlclient-1.4.2-cp37-cp37m-win32.whl"</p>
<p>this command is to install all tools by wheel</p>
<p>If you are not using python3.7, you may able to find a version which fix for you . <a href="https://www.lfd.uci.edu/~gohlke/pythonlibs/#mysqlclient">Link</a></p>
<p>cp37 means python 3.7, cp36 means python3.6 and so on.</p>
<p>After install the wheel, you should able to "pip install Flask-mysqldb"</p>
<hr>
<p>go to the link of the file, command to run is:</p>
<p>"py app.py" or "python app.py"</p>
<p>It should run successfully</p>
<h1>ENJOY!</h1>
<hr>
