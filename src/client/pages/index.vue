<template>
  <section class="container">
    <div>
      <h1 class="title">
        ttt
      </h1>
      <h2 class="subtitle">
        Welcome to the iView + Nuxt.js template
      </h2>
      <div class="links">
        <Button
          type="primary"
          target="_blank"
          to="https://nuxtjs.org/"
        >Documentation</Button>
        <Button
          target="_blank"
          to="https://github.com/nuxt/nuxt.js"
        >GitHub</Button>
        <Button
          target="_blank"
          to="https://www.iviewui.com/"
        >iView</Button>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  components: {},
};
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}
.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}
.links {
  padding-top: 15px;
}
</style>