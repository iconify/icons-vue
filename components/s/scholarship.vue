<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xb9_77bil"/><circle class="pf8xrvdha"/><circle class="kp330nbbl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:scholarship" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kp330nbbl {
  cx: 16.75px;
  cy: 16.5px;
  r: 2px;
}

.pf8xrvdha {
  cx: 16.75px;
  cy: 16.5px;
  r: 4.5px;
}

.xb9_77bil {
  d: path("m11.4 3.69l5.95 2.87q.9.44 0 .88l-5.95 2.87q-.9.44-1.8 0L3.65 7.44q-.9-.44 0-.88L9.6 3.69q.9-.44 1.8 0M6.25 9v3.5c1 1 2.5 1.5 4.25 1.5");
}

</style>
