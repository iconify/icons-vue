<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="csiuwxz_l"/><circle class="dtaoxebzb"/><path class="q492c2byv"/><rect class="ca7bvvass"/><path class="ap3qcob6l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:secure-connection" /></template>
<style>
.ap3qcob6l {
  d: path("M10.5 10.5V9a1.5 1.5 0 0 1 3 0v1.5");
}

.ca7bvvass {
  width: 6px;
  height: 5px;
  x: 9px;
  y: 10.5px;
  rx: 1.25px;
}

.csiuwxz_l {
  cx: 4.75px;
  cy: 13px;
  r: 2px;
}

.dtaoxebzb {
  cx: 19.25px;
  cy: 13px;
  r: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q492c2byv {
  d: path("M6.75 13H9m6 0h2.25");
}

</style>
