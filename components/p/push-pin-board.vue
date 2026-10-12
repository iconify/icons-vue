<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="zyt56mbrm"/><path class="t1ruryb_u"/><circle class="ix5kygeym"/><circle class="htd5wpb8c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:push-pin-board" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.htd5wpb8c {
  cx: 16px;
  cy: 11px;
  r: 1.5px;
}

.ix5kygeym {
  cx: 8px;
  cy: 8.5px;
  r: 1.5px;
}

.t1ruryb_u {
  d: path("M6.5 8.5H5.25v8.25h5.5V8.5H9.5m5.25 2.5h-1.5v6.25h5.5V11H17.5");
}

.zyt56mbrm {
  width: 18.5px;
  height: 16.5px;
  x: 2.75px;
  y: 3.75px;
  rx: 2px;
}

</style>
