- 👋 Hi, I’m @ysn52
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
ysn52/ysn52 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

<html>
<head>
<title>seçenek başlığı</title>
</head>
<body>
<form method="POST" action="login.php">

<label for="fname">first name:</label>
<input type="text" id="fname" name="fname"><br>
<label for="lname">last name:</label>
<input type="text" id="lname" name="lname">
<input type="submit">

</form>

<form>

<input type="checkbox" id="volvo" name="volvo">
<label for="volvo"> volvo sahibiyim</label><br>

<input type="checkbox" id="BMW" name="BMW">
<label for="BMW">BMW sahibiyim</label><br>

<input type="checkbox" id="mercedes" name="mercedes">
<label for="mercedes">mercedes sahibiyim</label>

</form>

<form>


<input type="radio" id="java" name="java">
<label for="java">java ogrenmek istiyorum</label><br>

<input type="radio" id="c#" name="c#">
<label for="c#">c# ogrenmek istiyorum</label><br>

<input type="radio" id="c++" name="c++">
<label for="c++"> c++ ogrenmek istiyorum</label><br>

<input type="radio" id="full-stack" name="full-stack">
<label for ="full-stack">full-stack devoloper olmak istiyorum</label> 


</form>

<form>
<label for="arabalarim">en beğendiğim araba</label> <BR><BR>
<select id="arabalarim" name="arabalarim" size="2"> 
<option>VOLVO</option>
<option>BMW</option>
<option>FİAT</option>
<option>AUDİ</option>
</select>
</form>
<textarea name="mesajim" rows="4" cols="12"> her öğün 5'er saat arayla yenilmeli</textarea>

<br><br>
<button type="button" onclick="alert('naber la!!!')">bas bana</button>

<form action="login.php">
<fieldset>
<legend>adam olacak kisi</legend>
<label for="adi">isminiz :</label>
<input type="text" id="adi" name="adi"> <br>

<label for="soyadi">soy isminiz : </label>
<input type="text" id="soyadi" name="soyadi"><br>

</fieldset>
</form>

<form action="login.php">

<input list="browsers">
<datalist id="browsers">
<option value="araba">
<input type="submit">

</datalist>

</form>

</body>
</html>

