<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l2la322mf"/><circle class="zg8gn-bqa"/><path class="ekrh4ibar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pleestracker" /></template>
<style>
.ekrh4ibar {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.52 25.53v3.66m1.19 1.18h3.65");
}

.l2la322mf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.69 30.66a1 1 0 0 0-1.19-.08A15.65 15.65 0 0 1 25.33 4.41a1 1 0 0 0-.54-1.87h-.27L24 2.5a21.5 21.5 0 1 0 20 29.32a1 1 0 0 0-.31-1.16m-30.17 6.5a6.79 6.79 0 1 1 6.79-6.79a6.8 6.8 0 0 1-6.79 6.79");
}

.zg8gn-bqa {
  cx: 13.52px;
  cy: 30.37px;
  r: 1.18px;
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
}

</style>
