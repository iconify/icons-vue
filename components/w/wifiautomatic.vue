<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tieua6bhf"/><path class="wtwkxebia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wifiautomatic" /></template>
<style>
.tieua6bhf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.25 23.51a14.44 14.44 0 0 0-18.45-.05v.05m9.2 3.54a7.61 7.61 0 1 0 7.61 7.61h0A7.61 7.61 0 0 0 24 27.05m14-9.36a22 22 0 0 0-28 0");
}

.wtwkxebia {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.48 12.4a29 29 0 0 0-37 0m15.23 26.47l3.39-8.44m3.24 8.47l-3.24-8.47m2.16 5.63h-4.43");
}

</style>
