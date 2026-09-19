<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rhd69p59j"/><path class="r2i_xct5i"/><circle class="rk1zf1bvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:photocircle" /></template>
<style>
.r2i_xct5i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.101 25.44A12.9 12.9 0 1 1 19.7 37.604l.002-12.162");
}

.rhd69p59j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.251 44.06C4.215 38.845.23 27.893 3.798 18.089C7.366 8.283 17.459 2.456 27.735 4.268C38.01 6.08 45.5 15.008 45.502 25.44");
}

.rk1zf1bvw {
  cx: 24.001px;
  cy: 25.441px;
  r: 4.3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
