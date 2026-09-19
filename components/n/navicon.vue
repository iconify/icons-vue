<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="nly6gvbwk"/><circle class="oz_-j7zmq"/><circle class="u7-e25b8d"/><path class="dmxwqo4nq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:navicon" /></template>
<style>
.dmxwqo4nq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.037 32.408a6.74 6.74 0 0 1-2.537-5.28a6.785 6.785 0 0 1 6.779-6.778c.113 0 .226.01.339.02c.77-4.364 4.57-7.682 9.16-7.682a9.3 9.3 0 0 1 7.776 4.2a5.7 5.7 0 0 1 1.53-.205a5.94 5.94 0 0 1 5.73 4.396a5.35 5.35 0 0 1 4.232 5.228a5.2 5.2 0 0 1-.862 2.896l.005.003s1.2.973 4.311.714c-1.207 1.699-3.17 3.717-6.865 3.625l.002.003a5.5 5.5 0 0 0 .318-1.849c0-.185-.01-.36-.03-.544a5.518 5.518 0 0 0-11.01.544c0 .709.133 1.387.38 2.013h-8.649a5.527 5.527 0 0 0-5.146-7.539c-3.04 0-5.514 2.476-5.514 5.526c0 .236.01.473.051.709");
}

.nly6gvbwk {
  width: 7.704px;
  height: 7.685px;
  x: 18.062px;
  y: 18.62px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.995px;
  ry: 1.995px;
}

.oz_-j7zmq {
  cx: 12.505px;
  cy: 31.698px;
  r: 3.595px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.u7-e25b8d {
  cx: 31.431px;
  cy: 31.717px;
  r: 3.595px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
