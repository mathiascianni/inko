<template>
    <nav class="navbar navbar-expand-lg navbar-light bg-light py-4">
        <div class="container-md">
            <a class="navbar-brand text-uppercase fs-1 fw-bold" href="#">My Webpage</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup"
                aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse justify-content-end" id="navbarNavAltMarkup">
                <div class="navbar-nav">
                    <a class="nav-link active" aria-current="page" href="#">Inicio</a>
                    <a class="nav-link" href="#">Productos</a>
                    <a class="nav-link" href="#">Contacto</a>
                    <a class="nav-link" href="#">About</a>
                </div>
            </div>
        </div>
    </nav>
</template>

<script>
export default {
    name: 'VueNav',
}
</script>

<style scoped>
ul {
    display: flex;
    gap: 2rem;
}

ul li {
    list-style: none;
}

a {
    text-decoration: none;
    color: #1d1d1d;
    transition: all .2s;
}

a:hover {
    color: #ffffff;
}
</style>