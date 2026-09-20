<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="zhcn2rb1d"/><rect class="hslkrf1jh"/><circle class="g2f95brax"/><path class="rdflh0bjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pivo" /></template>
<style>
.g2f95brax {
  cx: 20.381px;
  cy: 17.488px;
  r: 0.75px;
  fill: currentColor;
}

.hslkrf1jh {
  width: 5.343px;
  height: 7.08px;
  x: 30.157px;
  y: 20.761px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.672px;
  ry: 2.672px;
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

.rdflh0bjc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.381 20.761v7.079M12.5 25.169a2.672 2.672 0 1 0 5.343 0v-1.737a2.672 2.672 0 1 0-5.343 0m0-2.671v10.686");
}

.zhcn2rb1d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.353 20.761l-2.671 7.079l-2.672-7.079");
}

</style>
