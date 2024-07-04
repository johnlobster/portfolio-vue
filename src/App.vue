<script setup>
import Header from './components/Header/Header.vue'
import AboutPage from './components/AboutPage/AboutPage.vue';
</script>

<template>
  <Header />
  <main>
    <AboutPage />
  </main>
</template>

<style scoped>

main {
  background-color: #FFFFF0;
}
body {
  background-image: url(./images/blueBackground.jpg);
  background-repeat: repeat;
  display: flex;
  min-height: 100vh;
  flex-direction: column;
  font-family: 'Alegreya Sans', sans-serif;
  font-size: 18px;
}

h1,
h2,
h3,
h4,
h5,
button {
  font-family: 'Alegreya Sans', sans-serif;
}

h3,
h4,
h5 {
  font-weight: bold;
}
header {
  line-height: 1.5;
}




</style>

<!-- @media (min-width: 1024px) {
header {
display: flex;
place-items: center;
padding-right: calc(var(--section-gap) / 2);
}

.logo {
margin: 0 2rem 0 0;
}

header .wrapper {
display: flex;
place-items: flex-start;
flex-wrap: wrap;
}
}
 -->