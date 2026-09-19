<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="elpky9bnq"/><path class="d7j8n0l4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ticktock-video-wallpaper" /></template>
<style>
.d7j8n0l4z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.622 33.012l-8.874-5.123v10.246z");
}

.elpky9bnq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.73 22.4c-5.827-.005-10.554 4.714-10.56 10.54c-.005 5.827 4.714 10.555 10.54 10.56c5.811.005 10.532-4.69 10.56-10.5V4.5c0 5.827 4.723 10.55 10.55 10.55");
}

</style>
