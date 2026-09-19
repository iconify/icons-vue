<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="gbkzdtx5x"/><path class="ix3o-pb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mouse" /></template>
<style>
.gbkzdtx5x {
  width: 28px;
  height: 39px;
  x: 10px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 14px;
  ry: 14px;
}

.ix3o-pb3e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10 20.233h28M24 4.5v15.733");
}

</style>
