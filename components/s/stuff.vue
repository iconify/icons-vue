<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="alv27gnpw"/><circle class="azhi__bko"/><path class="a-z5fpb6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:stuff" /></template>
<style>
.a-z5fpb6s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.626 11.962l2.226 2.418l6.078-5.813m6.57 19.036a19.66 19.66 0 0 1-21.477.343a19.41 19.41 0 0 1-8.814-19.421m4.835 30.969A31 31 0 0 1 4.5 25.93");
}

.alv27gnpw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.458 9.008A3.99 3.99 0 0 1 43.5 12.5v23c0 2.216-1.784 4-4 4h-31c-2.216 0-4-1.784-4-4v-23c0-2.216 1.784-4 4-4v0h15.219");
}

.azhi__bko {
  cx: 32.5px;
  cy: 11.5px;
  r: 9.3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
