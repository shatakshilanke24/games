# games
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="games.css">
    <title>Document</title>
    *{
    margin:0%;
    padding:0%;
}
.container
{

    background-image:url(images.jpg);
    width:1400px;
    height: 650px;
    background-size: cover;
    background-attachment: fixed;  
    background-color: rgba(49, 96, 197, 0.514);
    /* opacity: 0.7;   */
    


    }
    .container h2{
        text-align: center;
        text-decoration: none;
        font-size: 70px;
        font-family: copperplate,papyrus,fantasy;
        color:  rgb(168, 45, 127);
        font-weight: 500px;
        padding-top: 120px;
        padding-right: 500x;
    }
    .content h1{
        text-align: center;
        padding-right: 80px;
        margin-top: 70px;
        color: white;
        font-style: normal;
        font-family: Arial, Helvetica, sans-serif;


    }
    .join h3{
        text-align: center;
        color: white;
        margin-top: 120px;
        padding-right: 90px;
    }
    .form1 form {
        text-align: center;
        /* margin-top: 30px; */
        padding-right: 100px;
        color: white;
        /* background-color: white; */

    }
    #form{
        color:black;
        box-sizing: border-box;
        text-align: center;
        margin-top: 30px;
        padding-right: 90px;
         padding: 10px;

    }
    input[type=text] {
        padding: 12px 20px;
        margin: 8px 0;
        box-sizing: border-box;
        background-color: blanchedalmond;
      }
      .placeholder{
          color: white;
          background-color: white;
      }
      .form1 button {
        background-color: rgb(163, 33, 120);
        border: none;
        color: white;
        padding: 15px 32px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 14px;
        /* margin: 4px 2px; */
        cursor: pointer;
      }
      .footer{
          text-align: center;
          color: white;
          padding-right: 70px;
          margin-top: 20px;
          
      }
<body>
    <div class="container">
        <h2>Pixel Relic Games</h2>
        
    
    <div class="content">
        <h1>Awesome Games Coming Soon..</h1>
    </div>
    <div class="join">
        <h3>Join the waiting list for the beta.We will keep you posted</h3>
    </div>
    <div class="form1">   
    <form>
        <input type="text" id="form" placeholder="your email here" required>
        <button onclick="myfunction()" >Notify Me</button>
    </div>
    <div class="footer">
        made with ❤️<br>
        cartoon city vectors by vecteezy
    </div>
    
    </div>
    </form>
    <script>
        function myfunction(){
            alert("email sent successfully..");

        }
        </script>
        


    
</body>
</html>
