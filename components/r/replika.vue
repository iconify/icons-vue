<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bg-jjcb7q"/><path class="k6mosu51y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:replika" /></template>
<style>
.bg-jjcb7q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.438 14.094l4.402 1.756l3.734-2.32l4.2 2.372l3.056-3.234");
}

.k6mosu51y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5c8.784 0 17.319 11.402 17.319 21.75A17.264 17.264 0 0 1 24 43.5m0-39c-8.784 0-17.319 11.402-17.319 21.75A17.264 17.264 0 0 0 24 43.5");
}

</style>
