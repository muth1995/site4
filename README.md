<script>
    function button1_onclick(){
        dvop.innerText="Sunday";
    }
    function button2_onclick(){
        spnop.innerHTML="Monday";
    }
    function button3_onclick(){
        tbx.value="Tuesday"; 
    }
    function button4_onclick(){
        document.title="Wednesday"; 
    }
    function button5_onclick(){
        alert("Thursday");
    }
    function button6_onclick(){
        document.write("Friday");
    }
    function button7_onclick(){
        console.log("Saturday");
    }
    function button8_onclick(){
        var s=prompt("Enter the Message");
        alert(s);
    }
    function button9_onclick(){
        var a=confirm("Do you go to webpage?");
        if(a){
            document.write=location.href="https://www.google.com";
        }
        else{
            document.write=location.href="about:blank";
        }
        
    }

</script>


<table border="1">
    <tr>
        <td>
            <input type="button" value="Button1" onclick="button1_onclick()">
        </td>
        <td>
            <input type="button" value="Button2" onclick="button2_onclick()">
        </td>
        <td>
            <input type="button" value="Button3" onclick="button3_onclick()">
        </td>
    </tr>
    <tr>
        <td>
            <input type="button" value="Button4" onclick="button4_onclick()">
        </td>
        <td>
            <input type="button" value="Button5" onclick="button5_onclick()">
        </td>
        <td>
            <input type="button" value="Button6" onclick="button6_onclick()">
        </td>    
    </tr>
    <tr>
        <td>
            <input type="button" value="Button7" onclick="button7_onclick()">
        </td>
        <td>
            <input type="button" value="Button8" onclick="button8_onclick()">
        </td>
        <td>
            <input type="button" value="Button9" onclick="button9_onclick()">
        </td>
    </tr>
    <tr>
        <td>
            <div id="dvop">wait..</div>    
        </td>
        <td>
            <span id="spnop">wait...</span>
        </td>
        <td>
            <input type="text" readonly="readonly" placeholder="wait.." id="tbx" width="10%">
        </td>       
    </tr>
</table>


