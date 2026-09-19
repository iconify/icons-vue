<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="yi8ch3bxo"/><path class="way1f1bll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wi-fi-toolkit" /></template>
<style>
.way1f1bll {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.5 13.5v-3a3 3 0 0 0-3-3h-9a3 3 0 0 0-3 3v3m10.96 16.98a5.39 5.39 0 0 0-6.89-.018v.019M24 32.689a2.162 2.162 0 1 0 2.163 2.162v0h0a2.16 2.16 0 0 0-2.162-2.162m6.747-5.946a10.6 10.6 0 0 0-13.494 0m16.736-3.924a15.676 15.676 0 0 0-20 0");
}

.yi8ch3bxo {
  width: 39px;
  height: 27px;
  x: 4.49px;
  y: 13.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3px;
}

</style>
