<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tl_hwib9j"/><path class="z382ngb7y"/><circle class="igss94b2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:valetudocompanion" /></template>
<style>
.igss94b2q {
  cx: 24px;
  cy: 17.974px;
  r: 2.803px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tl_hwib9j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.02 6.483a18.5 18.5 0 0 1-4.13 23.42C32.454 32.787 25.879 35.972 24 41.518c-2.064-5.51-8.451-8.73-11.891-11.616a18.5 18.5 0 0 1-4.13-23.42");
}

.z382ngb7y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.409 17.974c0 4.644-4.526 7.01-8.409 9.53c-3.769-2.409-8.409-4.886-8.409-9.53a8.409 8.409 0 0 1 16.818 0");
}

</style>
