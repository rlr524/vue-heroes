<template>
  <div class="navbar-menu">
    <div class="navbar-end">
      <div class="navbar-item">
        <div class="buttons">
          <a :href="gitURL" target="_blank" rel="noopener noreferrer">
            <i class="fab fa-github fa-2x" aria-hidden="true"></i>
          </a>
          <a :href="twitURL" target="_blank" rel="noopener noreferrer">
            <i class="fab fa-twitter fa-2x" aria-hidden="true"></i>
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeaderBarLinks',
  data() {
    return {
      gitURL: 'https://github.com/johnpapa/vue-getting-started',
      twitURL: 'https://www.twitter.com/emiyaconsulting',
    };
  },
  methods: {},
};
</script>

<style scoped></style>
