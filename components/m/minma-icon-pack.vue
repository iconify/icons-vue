<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(27.837 12.59 19.538)" class="twcxukbrg"/><circle class="ze7r_2bzr"/><path class="hu-5mccgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:minma-icon-pack" /></template>
<style>
.hu-5mccgc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.928 37.197l-1.84 3.483a3.412 3.412 0 1 1-6.035-3.187l9.886-18.718m1.322-2.505l4.727-8.95a3.412 3.412 0 1 1 6.035 3.187L19.165 34.853m9.395 2.669l-.836 1.585a3.412 3.412 0 1 1-6.035-3.187l6.698-12.684m1.323-2.504l1.54-2.916a3.412 3.412 0 1 1 6.035 3.187l-7.51 14.217");
}

.twcxukbrg {
  width: 6.825px;
  height: 17.744px;
  x: 9.177px;
  y: 10.667px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.412px;
  ry: 3.412px;
}

.ze7r_2bzr {
  cx: 37.96px;
  cy: 32.936px;
  r: 3.412px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
