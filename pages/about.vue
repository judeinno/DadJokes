<template>
  <div>
    <h1>About Dad Jokes</h1>
    <p>This is an app that displays corny dad jokes</p>
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: "About the App",
      meta: [
        {
          hid: "Description",
          name: "Description",
          content: "Best place for corny dad"
        }
      ]
    };
  }
};
</script>

<style lang="scss" scoped>
</style>
