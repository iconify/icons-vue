<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wew5m6bfr"/><path class="izj36mb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:native-a" /></template>
<style>
.izj36mb4t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.77 28.667v-10.01l8.321 10.01v-10.01");
}

.wew5m6bfr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.434 7.298S27.715 40.34 15.692 40.703c-13.99-.165-13.869-33.285 2.17-33.405C31.852 7.504 28.39 40.22 37.4 40.1c1.604.024 3.063-1.077 5.101-5.029");
}

</style>
