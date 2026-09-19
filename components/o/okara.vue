<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="psw3qubjv"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:okara" /></template>
<style>
.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.psw3qubjv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.405 30.674a1.644 1.644 0 0 1-.59-2.358l5.613-9.015m6.293 5.394l-8.909 5.752c-.676.438-1.39.832-2.407.227c-1.675 2.06-4.68 5.885-2.483 8.504c1.795 2.139 5.049.793 7.668-1.384c2.778-2.305 7.658-6.16 9.581-3.938c1.66 1.92.613 5.548-.264 8.644M23.14 13.534a6.81 6.81 0 1 1 9.63 9.63m-7.162-2.612c4.705 4.286 8.031 2.102 8.031 2.102a7.35 7.35 0 0 1-5.147 2.082c-4.01 0-7.265-3.167-7.265-7.075a6.97 6.97 0 0 1 1.807-4.672s-2.132 3.273 2.574 7.56z");
}

</style>
