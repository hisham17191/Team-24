# Team-24


<html>
<head>
<title>Javascript Login Form Validation</title>
<!-- Include CSS File Here -->
<link rel="stylesheet" href="D://JavaScript/javascript_login/style.css"/>
<!-- Include JS File Here -->
<script src="D://JavaScript/javascript_login/login.js"></script>
</head>
<body>
<div class="container">
<div class="main">
<h2>Javascript Login Form Validation</h2>
<form id="form_id" method="post" name="myform">
<label>User Name :</label>
<input type="text" name="username" id="username"/>
<label>Password :</label>
<input type="password" name="password" id="password"/>
<input type="button" value="Login" id="submit" onclick="validate()"/>
</form>
<span><b class="note">Note : </b>For this demo use following username and password. <br/><b class="valid">User Name : Formget<br/>Password : formget#123</b></span>
</div>
</div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>

<!DOCTYPE html>
<html">
<head>
    
    <title></title>
</head>
<body>
<?php
 include = 'D:/JavaScript/javascript_login/dbh.inc.php';
?>
<?php
    $sql = "SELECT * FROM users;";
    $result = mysqli_query($conn, $sql);
    $resultCheck = mysqli_num_rows($result); 

    if($resultCheck > 0){
        while($row = mysqli_fetch_assoc($result)){
            echo $row['user_uid'] . "<br>";
        }
    }
?>

</body>
</html>
<?php
$dbServername = "locahost";
$dbUsername = "root";
$dbPassword = "";
$dbName = "loginsystem";
$conn = mysqli_connect($dbServername, $dbUsername, $dbPassword, $dbName);
CREATE TABLE users (
    user_id int(11) AUTO_INCREMENT PRIMARY  KEY not null,
    user_first varchar(256) not null,
    user_last varchar(256) not null,
    user_email varchar(256) not null,
    user_uid varchar(256) not null,
    user_pwd varchar(256) not null,
);

INSERT INTO users (user_first, user_last, user_email, user_uid, user_pwd)
    VALUES ('Danial', 'Nielsen', 'usemmtuts@gmail.com', 'Admin', 'test123');
    <title>حاوية ذكية</title>
    <h1>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;أهلا و سهلا بكم في الحاوية الذكية</h1>
    <img height="560px" width="560px" src="C:\Users\Dell\OneDrive - Majma'ah University\Pictures\firstpagehail.jfif">
    <form action="secondpage.html">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<button>START</button></form>
</head>
<body>
    
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <h1>هنا تقسم الحياوية إلى قسمين</h1>
    <img height="250" width="250" src="C:\Users\Dell\OneDrive - Majma'ah University\Desktop\secondpafehail.jfif">
    <form action="thirdpage.html">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<button>أطعمة</button></form>
    <img height="250" width="250" src="C:\Users\Dell\OneDrive - Majma'ah University\Desktop\secondpafehail2.jfif">
    <form action="forthpage.html">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<button>مواد قابلة لتدوير</button></form>
    <img height="250px" width="250px" src="C:\Users\Dell\OneDrive - Majma'ah University\Pictures\firstpagehail.jfif">
    <form action="firstpagehail.html">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<button>Home</button></form>
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
    <title>الاطعمه</title>
    <h1>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;الأطعمه</h1>
    <img height="250" width="250" src="C:\Users\Dell\OneDrive - Majma'ah University\Desktop\secondpafehail.jfif"><br>
    <img height="250px" width="250px" src="C:\Users\Dell\OneDrive - Majma'ah University\Desktop\place.jfif">
    <form action="placepage.html">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<button>موقع الحاوية</button></form>
    <img height="250px" width="250px" src="C:\Users\Dell\OneDrive - Majma'ah University\Pictures\firstpagehail.jfif">
    <form action="firstpagehail.html">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<button>Home</button></form>
</head>
</body>
    
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
    <title>الاطعمه</title>
    <h1>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;الأطعمه</h1>
    <img height="250" width="250" src="C:\Users\Dell\OneDrive - Majma'ah University\Desktop\secondpafehail.jfif"><br>
    <img height="250px" width="250px" src="C:\Users\Dell\OneDrive - Majma'ah University\Desktop\universtyhail.jfif">
    <form action="universtypage.html">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<button>جامعة حائل</button></form>
    <img height="250px" width="250px" src="C:\Users\Dell\OneDrive - Majma'ah University\Desktop\hosptailhail.jfif">
    <form action="hosptailhail.html">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<button>مستشفى  حائل</button></form>
    <img height="250px" width="250px" src="C:\Users\Dell\OneDrive - Majma'ah University\Desktop\parkhail.jfif">
    <form action="parkhail.html">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<button>منتزة حائل</button></form>
    <img height="250px" width="250px" src="C:\Users\Dell\OneDrive - Majma'ah University\Pictures\firstpagehail.jfif">
    <form action="firstpagehail.html">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<button>Home</button></form>
</head>
</body>
    
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>

    <img height="250px" width="250px" src="C:\Users\Dell\OneDrive - Majma'ah University\Desktop\universtyhail.jfif">
    <h1>ما هي هويتك</h1>
    <img height="250px" width="250px" src="C:\Users\Dell\OneDrive - Majma'ah University\Desktop\farmer.jfif">
    <form action="farmer.html">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<button>مزارع</button></form>
    <img height="250px" width="250px" src="C:\Users\Dell\OneDrive - Majma'ah University\Desktop\citzen.jfif">
    <form action="citzen.html">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<button>مواطن</button></form>
    <img height="250px" width="250px" src="C:\Users\Dell\OneDrive - Majma'ah University\Pictures\firstpagehail.jfif">
    <form action="firstpagehail.html">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<button>Home</button></form>
</head>
</body>
    
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>

    <img height="250" width="250" src="C:\Users\Dell\OneDrive - Majma'ah University\Desktop\secondpafehail.jfif"><br>
    <img height="250px" width="250px" src="C:\Users\Dell\OneDrive - Majma'ah University\Desktop\farmer.jfif">
    <h1>إن السميد جاهز أو المواد جاهزه في الوقت المناسب</h1>
    <h1>   في الوقت المناسب الرجاء وضع مبلغ المواد أو السميد</h1>
    <img height="250px" width="250px" src="C:\Users\Dell\OneDrive - Majma'ah University\Pictures\firstpagehail.jfif">
    <form action="firstpagehail.html">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<button>Home</button></form>
</head>
</body>
    
</body>
</html>

#include<iostream>
using namespace std;
int main()
{
	cout<<"welcome to smart trash\n";
	char x,y;
	cout<<"choice the place you want to through your trash\n";
	cout<<" univerty (u) park (p) hospitail (H)\n";
	cin>>x;
	if(x=='u')
	{
	cout<<"choice your identy \n";
	cout<<"farmer (f) citzen (c)\n";
	cin>>y;
	if(y=='f')
	cout<<"entry the mony to take the stuff at time";
	if(y=='c')
	cout<<"take the mony for putting the stuff at time";
	}if(x=='p')
	{
	cout<<"choice your identy \n";
	cout<<"farmer (f) citzen (c)\n";
	cin>>y;
	if(y=='f')
	cout<<"entry the mony to take the stuff at time";
	if(y=='c')
	cout<<"take the mony for putting the stuff at time";
	}if(x=='H')
	{
	cout<<"choice your identy \n";
	cout<<"farmer (f) citzen (c)\n";
	cin>>y;
	if(y=='f')
	cout<<"entry the mony to take the stuff at time";
	if(y=='c')
	cout<<"take the mony for putting the stuff at time";}
}
  ![image](https://user-images.githubusercontent.com/79914254/112681344-a1b64580-8e7f-11eb-8dd9-0b88b71f2b78.png)
  
  نحن نكتب برنامج يحث على النظافة برد مالي يكون راجع للبرنامج ذاته الا و هو الحاوية الذكية حيث يقوم المستخدم بتسجيل دخوله في التطبيق لتظهر عنده حاويات قريبة منه يقوم المستخدم بتعريف نفسه بكونه مواطن او صاحب مزرعة او صاحب مصنع تدوير بعد ان يحدد هويته و يختار الحاوية  المناسبة له يكون على المواطن في كل مرة يرمي يستلم مبلغ و المزارع و صاحب المصنع يضعون المبلغ لاستلام السميد او المواد التي تحتاج تدوير في الوقت المناسب .  

  
