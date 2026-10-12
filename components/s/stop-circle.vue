<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dbgvcxwad"/><rect class="p27dfseqo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:stop-circle" /></template>
<style>
.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p27dfseqo {
  width: 6px;
  height: 6px;
  x: 9px;
  y: 9px;
  rx: 1.25px;
}

</style>
