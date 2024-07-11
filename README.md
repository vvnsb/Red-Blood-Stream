

Red Stream is a full stack website project based on online blood donation. This  is a responsive and userfriendly website for making the process of blood donation easy.



# Screenshot
![image](https://github.com/vvnsb/Red-Blood-Stream/assets/103960216/629746fa-2833-479e-9a29-9b12892317e0)



# How you run this full website on your local computer ?

You can download and use xampp or WampServer to run a web server on your PC. After that start Apache and Mysql services and now you successfully made your PC into a server.<br>
You need to download and extract this project into xampp>htdocs folder.<br>
Now type localhost in your browser and enter and go to phpMyAdmin section. There you need to add a new database named 'redstream_db'. Inside that create 2 tables named 'registered_users' and 'response_back'.<br>
Inside registered_users table create the following columns:-  name, email, phone, password, bloodgroup, gender, birthdate, weight(kg), state, zipcode, district, area, landmark, donations, and received. All of them needs to be VARCHAR datatype except weight(kg) and zipcode is int datatype and birthdate is date datatype.<br>
In response_back table create only one column named email.<br>
And now  you are good to go. If you sucsessfully extracted the project file into htdocs folder of xampp, you can just run localhost/YourFolderName in your browser and you can see the and experience the  project live.





