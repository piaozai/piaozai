# piaozai
ceshi
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>案例聊天框</title>
<style>
#div1{ width:300px; height:300px; border:1px solid #000;}
</style>
</head>

<body>
<div id="div1"></div>
<input id="txt" type="text" />
<input id="btn" type="button" value="发送" /> 
</body>
</html>
<script>
window.onload=function()
{
	var oDiv=document.getElementById("div1");
	var oTxt=document.getElementById("txt");
	var oBtn=document.getElementById("btn");
	oBtn.onclick=function()
	{
		oDiv.innerHTML=oDiv.innerHTML+"<span>TZ-芝士</span><p>"+oTxt.value+"</p>";
		oTxt.value="";
	}
}
</script>
