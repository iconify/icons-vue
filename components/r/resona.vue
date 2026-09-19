<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ltev1xcho"/><path class="abws9vbtu"/><circle class="m3f0hy_oe"/><path class="opqadoe1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:resona" /></template>
<style>
.abws9vbtu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.287 13.954h28.664v2.842H7.287zm0 5.805h7.196v5.745H7.287zm14.926 6.33h1.089m2.721 0h1.089");
}

.ltev1xcho {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.347 34.088H8.282A3.777 3.777 0 0 1 4.5 30.307v-16.81a3.786 3.786 0 0 1 3.782-3.781H35.2a3.786 3.786 0 0 1 3.781 3.781v10.468");
}

.m3f0hy_oe {
  cx: 36.042px;
  cy: 30.826px;
  r: 7.458px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.opqadoe1v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.042 34.596v-7.54m-3.77 3.77h7.539");
}

</style>
