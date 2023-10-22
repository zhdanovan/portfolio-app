<template>
  <div class="navbar">
    <div class="logo-container">
      <img src="../assets/logo.svg" class="logo" alt="Логотип" />
      <div class="text">ZHDANOVAN</div>
    </div>
    <!-- <img src="../assets/logo.svg" class="logo" alt="Логотип" /> -->
    <div class="wrapper">
      <router-link to="/" class="nav-link">Home</router-link>
      <router-link to="/about" class="nav-link">About</router-link>
      <router-link to="/projects" class="nav-link">Projects</router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: "HomePage",
};
</script>
<style>
.navbar {
  display: flex;
  align-items: center;
  background: none;
  justify-content: center;
  gap: 8%;
}
.nav-link {
  text-decoration: none;
  text-align: center;
  font-family: "Rostov", sans-serif;
  font-size: 48px;
  color: #2f7a78;
}
.logo {
  margin-left: -5%;
}
logo-container {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.text {
  font-family: Rostov;
  font-size: 32px;
  font-style: normal;
  font-weight: 400;
  line-height: 74%;
  color: #2f7a78;
}
.wrapper {
  display: flex;
  gap: 15%;
}
</style>
