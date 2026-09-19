<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="obvjt6pao"/><path class="yeedo2bpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yearly-progess" /></template>
<style>
.obvjt6pao {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.597 21.654h36.806c1.162 0 2.097.935 2.097 2.096v.5a2.09 2.09 0 0 1-2.097 2.096H5.597A2.09 2.09 0 0 1 3.5 24.25v-.5c0-1.161.935-2.096 2.097-2.096");
}

.yeedo2bpq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.597 21.654H28.07c1.161 0 2.097.935 2.097 2.096v.5a2.09 2.09 0 0 1-2.097 2.096H5.597A2.09 2.09 0 0 1 3.5 24.25v-.5c0-1.161.935-2.096 2.097-2.096");
}

</style>
