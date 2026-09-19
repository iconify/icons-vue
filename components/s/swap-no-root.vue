<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="hclugdb3z"/><rect class="wqaaj6blr"/><path class="s7521cc9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:swap-no-root" /></template>
<style>
.hclugdb3z {
  width: 26px;
  height: 26px;
  x: 11px;
  y: 10.998px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3px;
  ry: 3px;
}

.s7521cc9c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.5 11V5.5m0 37V37m-11-26V5.5m0 37V37M37 29.5h5.5m-37 0H11m26-11h5.5m-37 0H11");
}

.wqaaj6blr {
  width: 9px;
  height: 9px;
  x: 19.5px;
  y: 19.498px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
  ry: 1px;
}

</style>
