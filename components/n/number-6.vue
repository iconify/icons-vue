<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><g class="y9tr6bcfx"><circle class="zep-sybwn"/><path class="gbi5mnisa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:number-6" /></template>
<style>
.gbi5mnisa {
  d: path("M28.832 17.951c-.884-1.156-2.23-1.951-4.46-1.951H24a5.3 5.3 0 0 0-5.3 5.3v5.4");
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

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zep-sybwn {
  cx: 24px;
  cy: 26.7px;
  r: 5.3px;
}

</style>
