<template>
  <div>
      <h1>
          About jokes
      </h1>
      <p>
          This app is a list of corny jokes
      </p>
  </div>
</template>

<script>
export default {
    head() {
        return {
            title: 'About the app',
            meta: [
                {
                    hid: "description",
                    name: "descriptive name",
                    content: "Best place for corny jokes",
                }
            ]  
        }
    }
}
</script>

<style>

</style>