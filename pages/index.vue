<template>
  <div>
    <Tutorial/>
    <div class="container">
      <div>
        <h1 class="title">
          Hello explorer
        </h1>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  components: {
    Tutorial: () => import('@/components/Tutorial.vue') // Assurez-vous que le chemin est correct
  }
}
</script>

<style scoped>

</style>
