<template>
  <h1>Resume Page</h1>
  <div><img src="/resumePage.png"/></div>
  <h2>A digital resume with a 3D flair. <a href="https://endearing-unicorn-b097ea.netlify.app/">See it here</a></h2>
  <br/><br/>

  <h1>Fully 3D Promotional Page</h1>
  <div><img src="/onePNG.png"/></div>
  <h2>A site I created to advertise my freelance work. <a href="https://snazzy-churros-95d36a.netlify.app/">See it here</a></h2>
  <br/><br/>

  <h1>Solar System Model</h1>
  <div><img src="/solarsystem.png"/></div>
  <h2>A model of the solar system I am currently working on. I plan on making it to scale while still being easy to percieve. <a href="https://shiny-gelato-786a5b.netlify.app/">See it here</a></h2>

  <br/><br/>

  <h1>Senior Seminar Project</h1>
  <div><img src="/tompademo.png"/></div>
  <h2>A VR tower defense game I created in Unity with a colleague for my senior project as an undergraduate student. <a href="https://www.youtube.com/watch?v=9WIJQ6QJ_xQ">See it here</a></h2>
</template>

<script>

export default {
  name: 'App',
  components: {
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

img {
  width: clamp(15em, 40vw, 25em);
  border-radius: 5vw;
}

a {
  color: limegreen;
}
</style>
