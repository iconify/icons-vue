<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="rei1ft7hr"/><circle class="eztvv1b0g"/><path class="ed32x3bop"/><path class="k6_nv8b4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mobiry-days" /></template>
<style>
.ed32x3bop {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.964 27.071L32.242 8.5l-7.088 12.276L18.067 8.5l-7.088 12.276");
}

.eztvv1b0g {
  cx: 39.5px;
  cy: 29.071px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.k6_nv8b4h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.242 20.5l-7.088 12.276L18.067 20.5l-6.103 10.571M4.5 37.484a24.6 24.6 0 0 1 8.75-1.955m2 .01c2.665.122 5.31.68 7.795 1.65M43.5 37.5a24.6 24.6 0 0 1-8.75 1.955m-2-.009a24.6 24.6 0 0 1-7.795-1.65");
}

.rei1ft7hr {
  cx: 8.5px;
  cy: 29.071px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
