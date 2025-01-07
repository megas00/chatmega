<html>
<head>
<meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
    <link href="assets/css/styletableshop.css" rel="stylesheet" type="text/css">
    <title>Seguimiento de Pedidos</title>
    <!--=== Favicon ===-->
    <link rel="shortcut icon" href="assets/img/ico.png" type="image/x-icon" />
    <link href="assets/css/styl.css" rel="stylesheet" type="text/css">
</head>
<body>
        
    <div class="menuContainer"></div>
    
    <button class="open-button" onclick="openForm()"><img class="imagehelp" src="assets/img/icon/helpmegasur.png"></img> <span style="color:#000; font-size:16px;font-weight: bolder;">Cont&aacutectanos</span></button>
    
    <div class="form-popup" id="myForm">
        
      <form action="/action_page.php" class="form-container">
        <div style="width:100%">
            <div style="display:inline-block;width:100px;"><button type="button" class="btn cancel" onclick="closeForm()">X</button></div>
            <div style="display:inline-block;width:100px;"><span><b>Ayuda </b></span></div>
        </div>
        
         <hr>
        <div class="container-sm">
            <div class="row pb-3">
                <div class="col">
                    <div class="help-button">
                        <img class="help-button--img" src="assets/img/icon/mapmegasur.png">
                        <span class="help-button--text"><a href="https://www.megasurcard.com.mx/estaciones-afiliadas.php" target="_blank">Ubicaciones</a></span>
                    </div>
                </div>
                
                <div class="col">
                    <div class="help-button">
                        <img class="help-button--img" src="assets/img/icon/encmegasur.png">
                        <span class="help-button--text">Encuestas</span>
                    </div>
                </div>
                
                <div class="col ">
                    <div class="help-button">
                        <img class="help-button--img" src="assets/img/icon/mamegasur.png">
                        <span class="help-button--text"><a href="https://megasurcardayuda.tawk.help/article/manuales">Manuales</a></span>
                    </div>
                </div>
            </div>
            
            <h5>Cont&aacutectanos</h5>
    
        <!-- Listas de categorias. -->
            <div class="row pb-2">
                <div class="col-2"><i class="fa fa-weixin" aria-hidden="true" style="font-size:30px;color:#1eb0f4;"></i></div>
                <div class="col-10 textos">| <a href="javascript:void(Tawk_API.toggle())"> CHAT EN LINEA </a></div>
            </div>
            <div class="row pb-2">
                <div class="col-2"><i class="fa fa-whatsapp" aria-hidden="true" style="font-size:30px;color:#0aa539;"></i></div>
                <div class="col-10 textos">| <a href="https://web.whatsapp.com/send/?phone=9995753315", target="_blank"> WHATSAPP</a></div>
            </div>
          </div>
          <!-- Fin Listas cat -->

        </div>
          
        
      </form>
    </div>

        <script>
        function openForm() {
          document.getElementById("myForm").style.display = "block";
        }
        
        function closeForm() {
          document.getElementById("myForm").style.display = "none";
        }
        </script>

</body>
    
<!--Start of Tawk.to Script-->
    <script type="text/javascript">
    var Tawk_API=Tawk_API||{}, Tawk_LoadStart=new Date();
    (function(){
        var s1=document.createElement("script"),s0=document.getElementsByTagName("script")[0];
    s1.async=true;
    s1.src='https://embed.tawk.to/6700250e256fb1049b1d11de/1i9c91gg9';
    s1.charset='UTF-8';
    s1.setAttribute('crossorigin','*');
    s0.parentNode.insertBefore(s1,s0);
    })();
    </script>
<!--End of Tawk.to Script-->
</html>
