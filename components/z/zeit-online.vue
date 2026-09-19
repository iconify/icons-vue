<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tkerdfcam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zeit-online" /></template>
<style>
.tkerdfcam {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.189 33.816L34.9 43.338L8.81 43.5L32.305 4.837M10.151 13.2l3.88-8.538l24.73-.162l-23.495 38.663");
}

</style>
