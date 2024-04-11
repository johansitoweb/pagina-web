<script>
    let alt="imagen-html";
    let src ="html.png";
    let javascript="javascript.png";
    let bootstrap="bootstrap.png";
</script>


<main>

    <div class="container" id="clsaoidos" style="margin: 5%;">
        
        <div class="row">
            <div class="col-sm-4">
                <img src="{src}" alt="{alt}" >
            </div>
            <div class="col-sm-4">
                <img src="{javascript}" alt="" >
            </div>
            <div class="col-sm-4">
                <img src="{bootstrap}" alt="" >
            </div>
        </div>
<br/>
        <div>
            <div class="row">
                <div class="col-sm-4">
                    <img src="vue.png" alt="" >
                </div>
                <div class="col-sm-4">
                    <img src="php.png" alt="" >
                </div>
                <div class="col-sm-4">
                    <img src="css.png" alt="" >
                </div>
            </div>
        </div>
    </div>
    <br/>
    
  
   

</main>

<style>
    :root{
        --bg-secondary:white;
    }

    #clsaoidos{
        font-display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        background-color: white;
        border-radius: 12px;
    }

</style>