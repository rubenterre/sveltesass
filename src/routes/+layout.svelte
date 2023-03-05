<script>

</script>

<nav>
    <ul>
        <li><a href="/">Inicio</a></li>
        <li><a href="/contacto">Contacto</a></li>
    </ul>
</nav>

<div class="container">
    <div class="row">
    <div class="col s6 center">
        <div class="caja-1 ">
            <h1>HOLA</h1>
            <p>Esto es una prueba</p>
        </div>
    </div>
    <div class="col s6 center">
        <div class="caja-2">
            <h1>MUNDO</h1>
            <p>Esto es una prueba</p>
        </div>
    </div>
    </div>
</div>



<slot/>


<style lang="scss">
    .caja-1{
        background-color: #ce1313;
        border-radius: 10px;
        padding: 5px;
        color: white;
    }
    .caja-2{
        background-color: #3ca718;
        border-radius: 10px;
        padding: 5px;
        color: white;
    }
</style>