<template>
  <vue-picture-swipe :items="items"></vue-picture-swipe>
</template>
<script>
  import VuePictureSwipe from 'vue-picture-swipe';
  export default {
    name: 'FoodPics',
    data() {
      return {
        items: [{
          src: 'http://via.placeholder.com/600x400',
          thumbnail: 'http://via.placeholder.com/64x64',
          w: 600,
          h: 400
        },
        {
          src: 'http://via.placeholder.com/1200x900',
          thumbnail: 'http://via.placeholder.com/64x64',
          w: 1200,
          h: 900
        }
      ]};
    }
  }
</script>