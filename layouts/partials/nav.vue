<template>
  <header>
    <nuxt-link to="/" class="logo">Learn Nuxt</nuxt-link>

    <nav>
      <ul>
        <li>
          <nuxt-link to="/">Home</nuxt-link>
        </li>
        <li>
          <nuxt-link to="about">About</nuxt-link>
        </li>
        <li>
          <nuxt-link to="services">Services</nuxt-link>
        </li>
        <li>
          <nuxt-link to="contact">Contact</nuxt-link>
        </li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {};
</script>

<style>
header {
  background: #3b8070;
  display: grid;
  grid-template-columns: repeat(2, auto);
}

.logo,
li a {
  padding: 1em 2em;
  display: block;
  text-transform: uppercase;
  text-decoration: none;
  font-weight: bold;
  color: white;
  font-size: 0.9em;
}

nav {
  justify-self: right;
}
ul {
  list-style-type: none;
}
li {
  display: inline;
}
li a {
  padding: 1em 2em;
  display: inline-block;
  background: rgba(0, 0, 0, 0.1);
}
</style>
