<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m56wr_5wd"/><circle class="cl53k1bhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:myaakash" /></template>
<style>
.cl53k1bhf {
  cx: 24.062px;
  cy: 7.948px;
  r: 0.75px;
  fill: currentColor;
}

.m56wr_5wd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 40.802c9.81-5.278 17.026-12.683 18.5-25.16c1.474 12.477 8.69 19.882 18.5 25.16");
}

</style>
