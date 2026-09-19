<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nxk4t1bjq"/><circle class="je7lidi_x"/><path class="xjvyf5l8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:poppy" /></template>
<style>
.je7lidi_x {
  cx: 17.5px;
  cy: 40.25px;
  r: 3.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nxk4t1bjq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.75 11h6.5v6.5h-6.5z");
}

.xjvyf5l8n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.75 30.5V24h13V4.5h-19.5v26z");
}

</style>
