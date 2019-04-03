<template>
    <section class="container">
        <h2><a>Galery</a></h2>
        <h2><a>About</a></h2>
    </section>
</template>

<style>

h2 a {
    padding-bottom: 1.05em;
    border-bottom-width: 1px;
    border-bottom-style: solid;
    border-bottom-color: rgba(36,36,36,.3);
    letter-spacing: 8px;
}
</style>

<script>
export default function(x) {
  return function constant() {
    var fs = require('fs');
    return x;
  };
}

// var files = fs.readdirSync('/assets/photos/');
// console.log(files);
   
</script>