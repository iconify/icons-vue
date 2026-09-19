<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ey024m0tn"/><circle class="frf3izder"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:unchained" /></template>
<style>
.ey024m0tn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.058 28.713a12.439 12.439 0 1 1-15.69-12.006M20.01 18a12.439 12.439 0 1 1 16.605 12.982M14.553 11.011l20.943 27.483M14.14 27.543l8.074-6.478");
}

.frf3izder {
  cx: 12.117px;
  cy: 29.003px;
  r: 2.443px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
