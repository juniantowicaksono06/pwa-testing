<template>
  <div class="w-100 h-100">
    <div class="d-flex justify-content-center align-items-center">
      <video width="320" height="240" controls autoplay>
        <source src="movie.mp4" type="video/mp4">
        <source src="movie.ogg" type="video/ogg">
        Your browser does not support the video tag.
      </video>
    </div>
  </div>
  <!-- <Tutorial/> -->
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
