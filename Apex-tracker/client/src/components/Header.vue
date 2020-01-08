<template>
  <header>
    <img :src="image" />
  </header>
</template>

<script>
export default {
  name: "Header",
  data() {
    return {
      image: require("@/assets/logo2.png")
    };
  }
};
</script>

<style scoped>
img {
  width: 300px;
}

@media (max-width: 700px) {
  img {
    display: block;
    margin: auto;
  }
}
</style>