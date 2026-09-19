<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="j745l8b8d"/><path class="gmg92710f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:minimal" /></template>
<style>
.gmg92710f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.75 23.34l2.57 2.57l5.07-5.07M4.71 9.87l2.58 2.57l5.07-5.07m4.22 2.57H43.5M16.58 23.38H43.5M16.58 36.81H43.5");
}

.j745l8b8d {
  cx: 8.32px;
  cy: 36.81px;
  r: 3.82px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
