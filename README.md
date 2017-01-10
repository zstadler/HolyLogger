<h1>Holyland Logger</h1>

**This is a super simple, one click, easy to use logging application for Holyland contest participants.**<br>

The main screen is simply a set of all the required fields in a qso.
<a href="https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/HolyLogger.png" target="_blank">
![Alt text](https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/HolyLogger.png?raw=true "HolyLogger Main Screen")
</a>

**_File->Export_** will allow you to export your log in ADIF format (.adi)**<br>
<a href="https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/export.png" target="_blank">
![Alt text](https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/export.png?raw=true "HolyLogger Main Screen")
</a>

**_Tools->Signboard_** will display your callsign and grid on a clean, seperate window so it is always in front of your eyes<br>
**_Tools->My Score_** will display your current estimated score<br>
<a href="https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/Signboard.png" target="_blank">
![Alt text](https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/Signboard.png?raw=true "HolyLogger Main Screen")
</a>

<h2>QRZ.COM Subscription</h2>
To take advantage of the qrz.com xml subscription, open the *.config* file and update your user name and password.<br>

```javascript
<setting name="qrz_username" serializeAs="String">
  <value>Your_QRZ_UserName</value>
</setting>
<setting name="qrz_password" serializeAs="String">
  <value>Your_QRZ_Password</value>
</setting>
```

<h2>Omni-Rig</h2>
<a href="http://www.dxatlas.com/omnirig/" target="_blank">omnirig</a> is a COM component for transceiver/receiver CAT control.<br>
If installed, HolyLogger uses omnirig to communicate with the radio (it just sends frequency requests).


<h2>Download</h2>
<a href="https://github.com/4Z1KD/HolyLogger/archive/master.zip" target="_blank">Download HolyLogger</a>

<h2>Author</h2>
Design and Code: **_Gil, 4Z1KD_**

Created: 2016-2017<br>


<script>
var list = document.getElementById("logo");
list.outerHTML = '<img src="https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/HolyLogger%20icon.png" width="156px" style="position:absolute; top:-80px;right:10px;background:transparent"/>';
</script>
<img src="https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/HolyLogger%20icon.png" width="1px" style="display:none;"/>
