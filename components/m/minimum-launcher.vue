<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="oh-q7qtwz"/><rect class="j6swy051u"/><rect class="x099_zptd"/><path class="ypm87sb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:minimum-launcher" /></template>
<style>
.j6swy051u {
  width: 16.586px;
  height: 16.586px;
  x: 25.914px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.oh-q7qtwz {
  width: 16.586px;
  height: 16.586px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.x099_zptd {
  width: 16.586px;
  height: 16.586px;
  x: 5.5px;
  y: 25.914px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.ypm87sb6b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.207 42.5V25.914m-8.293 8.293H42.5");
}

</style>
