# GreatestCommonDivisor
<!DOCTYPE html>
<html>
<body>

<h2>GreatestCommonDivisor</h2>

<p id="demo"></p>

<script>
function myFunction(var n,var n1,var I,var HCF,var LCM)
for(i=2;i<n;i++)
if(n%i==0 & n1%i==0)
{
	HCF=I;
	break;
}
if(HCF==0)
{
	HCF=1;
	LCM=(n*n1)/HCF;
}

document.getElementById("demo").innerHTML="The HCF and LCM values are" + "HCF" + "LCM";
</script>

</body>
</html>
