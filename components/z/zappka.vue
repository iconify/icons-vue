<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uo47pyvli"/><path class="ecw67uspn"/><circle class="iqaq-x2uv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zappka" /></template>
<style>
.ecw67uspn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.621 21.35h4l-4 5.3h4m19.609-8v8m0-1.699l3.622-3.604m-2.469 2.457l2.847 2.834M17.124 24.65a2 2 0 1 1-4 0v-1.3a2 2 0 1 1 4 0m0 3.3v-5.3m23.256 3.3a2 2 0 1 1-4 0v-1.3a2 2 0 1 1 4 0m-.001 3.3v-5.3m-21.177 3.3a2 2 0 1 0 4 0v-1.3a2 2 0 1 0-4 0m0-2v8m6.014-4.7a2 2 0 1 0 4 0v-1.3a2 2 0 1 0-4 0m0-2v8m-12.085 1.493a14.64 14.64 0 0 0 16.077 0");
}

.iqaq-x2uv {
  cx: 9.621px;
  cy: 19.6px;
  r: 0.75px;
  fill: currentColor;
}

.uo47pyvli {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 42.5h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4");
}

</style>
