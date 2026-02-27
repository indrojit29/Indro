<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Professional Profile</title>

<style>
body{
    margin:0;
    font-family: 'Segoe UI', sans-serif;
    background: linear-gradient(135deg,#0f2027,#203a43,#2c5364);
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
}

.card{
    background:#ffffff;
    width:340px;
    border-radius:20px;
    box-shadow:0 15px 40px rgba(0,0,0,0.4);
    padding:25px;
    text-align:center;
}

.profile-img{
    width:110px;
    height:110px;
    border-radius:50%;
    border:4px solid #2c5364;
    object-fit:cover;
}

h2{
    margin:15px 0 5px;
    color:#222;
}

.info{
    text-align:left;
    margin-top:15px;
}

.info p{
    margin:8px 0;
    font-size:14px;
    color:#444;
}

.buttons{
    margin-top:20px;
}

.btn{
    display:inline-block;
    padding:10px 18px;
    margin:5px;
    border-radius:25px;
    text-decoration:none;
    font-size:14px;
    color:white;
    transition:0.3s;
}

.instagram{
    background:#e1306c;
}

.contact{
    background:#2c5364;
}

.btn:hover{
    opacity:0.8;
}
</style>

</head>
<body>

<div class="card">

    <img src="https://via.placeholder.com/110" class="profile-img">

    <h2>Your Name</h2>

    <div class="info">
        <p><strong>Institution:</strong> Your College Name</p>
        <p><strong>Class:</strong> Inter 1st Year</p>
        <p><strong>Age:</strong> 16</p>
        <p><strong>Hobbies:</strong> Gaming, Coding, Anime</p>
        <p><strong>Contact:</strong> 01XXXXXXXXX</p>
    </div>

    <div class="buttons">
        <a href="https://instagram.com/yourusername" target="_blank" class="btn instagram">Instagram</a>
        <a href="tel:01XXXXXXXXX" class="btn contact">Call Me</a>
    </div>

</div>

</body>
</html>