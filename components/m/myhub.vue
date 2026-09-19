<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="jgt_9g8bm"/><path class="k9npzwbtp"/><path class="gs9ewefws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:myhub" /></template>
<style>
.gs9ewefws {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.343 20.026h3.8a3.463 3.463 0 0 1 3.475 3.461v15.538a3.466 3.466 0 0 1-3.475 3.475h-9.916a3.474 3.474 0 0 1-3.475-3.475v-4.268");
}

.jgt_9g8bm {
  width: 16.857px;
  height: 22.476px;
  x: 8.382px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.466px;
  ry: 3.466px;
}

.k9npzwbtp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.238 12.282h3.63a3.48 3.48 0 0 1 3.475 3.475v15.538a3.47 3.47 0 0 1-3.474 3.462h-9.917a3.47 3.47 0 0 1-3.474-3.462v-3.318");
}

</style>
