<html>
## Welcome to Tech Firm Leadership 

Hi! Each week students 
For instructors, what do you want the weekly code to be? 


<form onsubmit="this.doSomething();">
    <input type="text" name="qr">
    <input type="submit">
</form>


Code of the day: <br>

<div id="qr_code">
<img src="https://chart.googleapis.com/chart?cht=qr&chl=MATMSG%3ATO%3Aieor171.berkeley%40gmail.com%3BSUB%3A%3BBODY%3AWEEK7%3B%3B&chs=180x180&choe=UTF-8&chld=L|2" 
rel='nofollow' alt='qr code' align="middle"><a href='http://www.qrcode-generator.de' border='0' style='cursor:default'  rel='nofollow'></a>
    </div>
Please display this code for students to scan and check in. <br>

This spreadsheet automatically tracks all attendance: <a href='https://docs.google.com/spreadsheets/d/11_kqC3xLnkT3evQBfSx_L7TmtgzeszhXTkMx8hyZRxg/edit?usp=sharing'>Attendance</a><br>

</html>
<script>
function doSomething() {
    document.getElementById("qr_code").innerHTML = 
    '<img id="qr_code" src="https://chart.googleapis.com/chart?cht=qr&chl=MATMSG%3ATO%3Aieor171.berkeley%40gmail.com%3BSUB%3A%3BBODY%3A" + qr +
        "%3B%3B&chs=180x180&choe=UTF-8&chld=L|2" rel='nofollow' alt='qr code' align="middle"><a href='http://www.qrcode-generator.de' border='0' style='cursor:default'  rel='nofollow'></a>';
    location.reload();
}
</script>
