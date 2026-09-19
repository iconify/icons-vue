<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eg99nbbfa"/><circle class="a6doftssb"/><circle class="o6ihs_bfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:waze" /></template>
<style>
.a6doftssb {
  cx: 14.52px;
  cy: 41.43px;
  r: 3.85px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.eg99nbbfa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.47 39.38a17.4 17.4 0 1 0-22-16.78a17.2 17.2 0 0 0 1.34 6.7h0c.08.21.19.41.29.62c1 2.41-.29 3.47-.29 3.47L2.77 40H11m7.14 0h5.55M28 18.44a3 3 0 0 1 3-3h0a3 3 0 0 1 3 3h0a3 3 0 0 1-3 3h0a3 3 0 0 1-3-3m-10.26 0a3 3 0 0 1 3-3h0a3 3 0 0 1 3 3h0a3 3 0 0 1-3 3h0a3 3 0 0 1-3-3m-.25 5.76a8.79 8.79 0 0 0 16.61 0");
}

.o6ihs_bfy {
  cx: 27.21px;
  cy: 41.43px;
  r: 3.85px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
