<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Apples Bananas</a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNavAltMarkup"
        aria-controls="navbarNavAltMarkup"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <div class="navbar-nav ">
          <a class="nav-link active" aria-current="page" href="#">Here</a>
          <a class="nav-link" href="#">Somewhere</a>
          <a class="nav-link" href="#">Everywhere</a>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'MainNav',
};
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,400;0,500;0,700;1,300&display=swap');

.navbar-brand {
  font-family: 'Open Sans', sans-serif;
  color: #5E047A;
}
.brand-modifier{
    
}
</style>
