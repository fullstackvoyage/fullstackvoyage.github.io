<template>
  <div id="hello">
    <section class="hero is-fullheight is-bold is-primary">

 <div class="hero-head">
    <nav class="navbar">
      <div class="container">
        <div class="navbar-brand">
          <a class="navbar-item">
            <span class="title is-3">FullStackVoyage</span>
          </a>
          <span class="navbar-burger burger" data-target="navbarMenuHeroA">
            <span></span>
            <span></span>
            <span></span>
          </span>
        </div>
        <div id="navbarMenuHeroA" class="navbar-menu">
          <div class="navbar-end">
            <a class="navbar-item is-active">
              Resources
            </a>
            <a class="navbar-item">
              Playgrounds
            </a>
            <a class="navbar-item">
              Dashboard
            </a>
            <span class="navbar-item">
              <a class="button is-primary is-inverted">
                Log In
              </a>
            </span>
          </div>
        </div>
      </div>
    </nav>
  </div>

      <!-- <div class="hero-head">
        <nav class="navbar">
          <div class="container">
            <div class="nav-left">
              <a class="nav-item">
                <strong>FullStackVoyage</strong>
              </a>
            </div>
            <span class="nav-toggle">
              <span></span>
              <span></span>
              <span></span>
            </span>
            <div class="nav-right nav-menu">
              <a class="nav-item is-active">
                Resources
              </a>
              <a class="nav-item">
                Playgrounds
              </a>
              <a class="nav-item">
                Dashboard
              </a>
              <span class="nav-item">
                <a class="button is-primary is-inverted">
                  <span>Log In</span>
                </a>
              </span>
            </div>
          </div>
        </nav>
      </div> -->

      <div class="hero-body" id="home-hero">
        <div class="container has-text-centered">
          <h3 class="title is-2">
            <strong>Learn. Prototype. Publish.</strong>
          </h3>
          <h4 class="subtitle is-4">software development resouces for adventurous devs</h4>
        </div>
      </div>

    </section>

    <section class="section">
      <div class="container">
        <h3 class="title is-2 has-text-centered">Features</h3>
        <div class="columns has-text-centered">
          <div class="column">
            <div class="box">
              <h2 class="title is-3">Resource Explorer</h2>
              <p class="subtitle is-5">
                explore technologies to plan your journey, curated snippets + syntax guides help you navigate
              </p>
              <p class="content is-small">
                Consectetur adipiscing elit. Fusce auctor metus a erat rutrum, pharetra hendrerit odio rhoncus. Nunc eget faucibus nulla, nec aliquam eros. Mauris et velit a sem pharetra commodo at id ante.
              </p>
            </div>
          </div>
          <div class="column">
            <div class="box">
              <h2 class="title is-3">Project Navigator</h2>
              <p class="subtitle is-5">feature planning + issue tracking + repository sync all from your browser</p>
              <p class="content is-small">Consectetur adipiscing elit. Fusce auctor metus a erat rutrum, pharetra hendrerit odio rhoncus. Nunc eget faucibus nulla, nec aliquam eros. Mauris et velit a sem pharetra commodo at id ante.</p>
            </div>
          </div>
          <div class="column">
            <div class="box">
              <h2 class="title is-3">Content Creation</h2>
              <p class="subtitle is-5">
                Generate outlines from your projects and supercharge your publishing with resources from your personal asset library
              </p>
              <p class="content is-small">
                Consectetur adipiscing elit. Fusce auctor metus a erat rutrum, pharetra hendrerit odio rhoncus. Nunc eget faucibus nulla, nec aliquam eros. Mauris et velit a sem pharetra commodo at id ante.
              </p>            </div>
          </div>
          <div class="column">
            <div class="box">
              <h2 class="title is-3">Interactive Playgrounds</h2>
              <p class="subtitle is-5">
                Jump straight into pre-configured environments with guided tutorials and push your creation to Github at any time.
              </p>
              <p class="content is-small">
                Consectetur adipiscing elit. Fusce auctor metus a erat rutrum, pharetra hendrerit odio rhoncus. Nunc eget faucibus nulla, nec aliquam eros. Mauris et velit a sem pharetra commodo at id ante.
              </p>            
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="hero is-dark">
      <div class="hero-body">
        <div class="container">
          <h1 class="title">
            Get Started!
          </h1>
          <h2 class="subtitle">
            It's free.
          </h2>
        </div>
      </div>
    </section>
    
    <!--<footer class="footer">
      <div class="container">
      </div>
    </footer>-->    
  </div>
</template>

<script lang="ts">
import { Vue, Component, Prop } from "vue-property-decorator";

@Component
export default class HelloWord extends Vue {
  msg = "Welcome to Your Vue.js App";
}
</script>

<style lang="scss" scoped>
#home-hero {
  background-image: url('data:image/svg+xml,%3Csvg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 80 80" width="80" height="80"%3E%3Cpath fill="%239C92AC" fill-opacity="0.2" d="M14 16H9v-2h5V9.87a4 4 0 1 1 2 0V14h5v2h-5v15.95A10 10 0 0 0 23.66 27l-3.46-2 8.2-2.2-2.9 5a12 12 0 0 1-21 0l-2.89-5 8.2 2.2-3.47 2A10 10 0 0 0 14 31.95V16zm40 40h-5v-2h5v-4.13a4 4 0 1 1 2 0V54h5v2h-5v15.95A10 10 0 0 0 63.66 67l-3.47-2 8.2-2.2-2.88 5a12 12 0 0 1-21.02 0l-2.88-5 8.2 2.2-3.47 2A10 10 0 0 0 54 71.95V56zm-39 6a2 2 0 1 1 0-4 2 2 0 0 1 0 4zm40-40a2 2 0 1 1 0-4 2 2 0 0 1 0 4zM15 8a2 2 0 1 0 0-4 2 2 0 0 0 0 4zm40 40a2 2 0 1 0 0-4 2 2 0 0 0 0 4z"%3E%3C/path%3E%3C/svg%3E');
}
</style>
