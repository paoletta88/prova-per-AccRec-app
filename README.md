di sotto il codice. l'app e' stata built da un collega. il mio task sarebbe di aggiungere un layout. volevo partire da componenti semplici, come il logo GE e aggiungere i colori aziendali.

mi sono bloccata subito :(


<HTML>
<HEAD>

<BODY>
   {background-color: rgba(255, 0, 0, 0.3);}

<img src="images\ge_monogram_primary_blue_RGB.png" alt="Loco" width="128" height="128">
  <TITLE></TITLE>

</HEAD>

<BODY>

  <DIV align="center">
	<H3>CAS Account Rec Audit (SSO ID: 212405588)</H3>
</DIV>
<style>
	TABLE {
  		border-style:solid;
        border-width:1px;
        border-color:#FFFFFF;
        padding: 0px;
		font-size: 11px;
	}
	TH {
  		background-color:#000055;
  		color: white;
		font-size: 11px;
	}
	TD{
            		border-style:solid;
            		border-width:1px;
            		border-color:#FFFFFF;
            		padding: 0px;
					font-size: 11px;
	}
	INPUT{
			font-size: 11px;
	}
	OPTION{
			font-size: 11px;
	}
	SELECT{
		font-size: 11px;
	}
	TEXTAREA{
		font-size: 10px;
	}
</style>

<pre><form id=UpdateForm action=accrecaudit.php onsubmit="return validateForm()" method=POST ><TABLE id='t01'><TR><TH HEIGHT='35'>ID</TH><TH HEIGHT='35'>ACCOUNT NAME</TH><TH HEIGHT='35'>MGMT<BR>ENTITY</TH><TH HEIGHT='35'>LEGAL<BR>ENTITY</TH><TH HEIGHT='35'>BUSINESS</TH><TH HEIGHT='35'>SUB<BR>BUSINESS</TH><TH HEIGHT='35'>ACCOUNT<BR>NO.</TH><TH HEIGHT='35'>RECON<BR>SSO</TH><TH HEIGHT='35'>ACCOUNT<BR>BAL</TH><TH HEIGHT='35'>CURR</TH><TH HEIGHT='35'>SRC</TH><TH HEIGHT='35'>AUDIT<BR>STATUS</TH><TH HEIGHT='35'>AUDIT<BR>RESULT</TH><TH HEIGHT='35'>FAILURE<BR>LEVEL</TH><TH HEIGHT='35'>AUDIT<BR>COMMENTS</TH></TR></TABLE><INPUT TYPE='hidden' NAME='reccount' VALUE=0></INPUT>


<DIV align="center">
	<INPUT TYPE="SUBMIT" NAME="UPDATE" VALUE="UPDATE" ONCLICK="validateForm()"></INPUT><INPUT TYPE="RESET" NAME="RESET" VALUE="RESET"></INPUT>
</DIV>
<p id="status" style="color:red"></p>
</form>

</HTML>
