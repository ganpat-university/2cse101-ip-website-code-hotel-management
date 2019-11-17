
function validation(){
var user=document.getElementById('user').value;
var user=document.getElementById('guest').value;
var user=document.getElementById('arrivald').value;
var user=document.getElementById('arrivalt').value;
var user=document.getElementById('depatured').value;
var user=document.getElementById('depaturet').value;
if(user==""){
document.getElementById('username').innerHTML="please the information";
return false;
}
if(user==""){
document.getElementById('arrivaldate').innerHTML="please the information";
return false;
}
if(user==""){
document.getElementById('arrivaltime').innerHTML="please the information";
return false;
}
if(user==""){
document.getElementById('noguest').innerHTML="please the information";
return false;
}
if(user==""){
document.getElementById('depaturedate').innerHTML="please the information";
return false;
}
if(user==""){
document.getElementById('depaturetime').innerHTML="please the information";
return false;
}
}
