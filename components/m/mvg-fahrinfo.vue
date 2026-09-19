<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h3ufa8bkt"/><rect class="wcd62ieam"/><circle class="qxrj0obtf"/><rect class="zgahq1b9e"/><circle class="x3x6dmp9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mvg-fahrinfo" /></template>
<style>
.h3ufa8bkt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.469 36.4v-2.902m0 1.827c0 .592-.485 1.075-1.075 1.075h0a1.077 1.077 0 0 1-1.076-1.074v-.7c0-.591.484-1.075 1.075-1.075h0a1.08 1.08 0 0 1 1.076 1.074m-4.235-1.127V36.4m0-1.827c0-.592.484-1.075 1.075-1.075h0m6.816 1.128c0-.591.483-1.075 1.074-1.075h0c.592 0 1.076.484 1.076 1.074V36.4m-4.3-2.902V36.4m0-1.773c0-.592.483-1.076 1.074-1.076h0c.592 0 1.076.484 1.076 1.075V36.4m-9.502 0v-4.3m-1.398 0h2.795m20.862 6.244c.66.793 1.453 1.189 2.642 1.189h1.585a2.65 2.65 0 0 0 2.641-2.641h0a2.65 2.65 0 0 0-2.641-2.643H33.39a2.65 2.65 0 0 1-2.64-2.64h0a2.65 2.65 0 0 1 2.64-2.642h1.586c1.188 0 1.98.264 2.64 1.188m-7.189-16.404h-1.772m1.772-.001c.591 0 1.075.484 1.075 1.075c0 .592-.484 1.075-1.075 1.075h-1.772v-4.3h1.773c.591 0 1.075.484 1.075 1.076a1.08 1.08 0 0 1-1.075 1.075zm2.453-2.15v2.85c0 .806.644 1.45 1.397 1.45s1.397-.645 1.397-1.451V11.6m1.432 3.817c.268.322.591.483 1.074.483h.646c.59 0 1.074-.484 1.074-1.075h0c0-.59-.484-1.074-1.074-1.074h-.7a1.08 1.08 0 0 1-1.074-1.075h0c0-.592.483-1.075 1.075-1.075h.645c.484 0 .806.107 1.074.483M10.25 8.366V15.5c0 2.019 1.616 3.635 3.5 3.635c1.885 0 3.5-1.616 3.5-3.635V8.366");
}

.qxrj0obtf {
  cx: 34.25px;
  cy: 13.75px;
  r: 8.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wcd62ieam {
  width: 16.5px;
  height: 16.5px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3px;
  ry: 3px;
}

.x3x6dmp9r {
  cx: 34.25px;
  cy: 34.25px;
  r: 8.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zgahq1b9e {
  width: 16.5px;
  height: 16.5px;
  x: 5.5px;
  y: 26px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3px;
  ry: 3px;
}

</style>
