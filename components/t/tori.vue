<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="pws04414a"/><circle class="sbm5qwbdb"/><path class="cy2dmfbqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tori" /></template>
<style>
.cy2dmfbqq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.523 21.499v7.4m-18.557-9.704v8.308c0 .771.625 1.396 1.396 1.396h.42m-3.282-7.4h2.932m2.668 2.793a2.793 2.793 0 0 1 5.585 0v1.815a2.793 2.793 0 0 1-5.585 0z");
}

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

.pws04414a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.768 24.292a2.793 2.793 0 0 1 2.792-2.793h0m-2.792 0v7.4");
}

.sbm5qwbdb {
  cx: 33.523px;
  cy: 18.078px;
  r: 0.75px;
  fill: currentColor;
}

</style>
