<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fkcp_6b5g"/><path class="r_y3w3bvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sidestep" /></template>
<style>
.fkcp_6b5g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.56 10.772C4.137 6.97 5.443 26.569 22.892 26.245c15.761-.292 19.802 20.306-14.452 15.539");
}

.r_y3w3bvu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.076 5.5l6.484 5.272l-6.452 5.304");
}

</style>
