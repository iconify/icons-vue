<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j_ly1ab2o"/><path class="dma80-b9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tiger-openspace" /></template>
<style>
.dma80-b9r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.5 10.86h4.914c7.564-.017 13.709 6.1 13.726 13.664V29.5c.017 7.563-6.101 13.708-13.665 13.725H18.5c-7.563.017-13.708-6.101-13.725-13.665v-4.974c-.017-7.563 6.1-13.709 13.664-13.726z");
}

.j_ly1ab2o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.586 4.775H29.5c7.564-.017 13.708 6.101 13.725 13.665v4.974c.017 7.564-6.1 13.709-13.664 13.726h-4.975c-7.563.017-13.709-6.1-13.726-13.664V18.5c-.017-7.563 6.101-13.708 13.665-13.725z");
}

</style>
