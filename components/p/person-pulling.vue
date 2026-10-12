<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="gg525p0gt"/><path class="mqoc1vb-o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:person-pulling" /></template>
<style>
.gg525p0gt {
  cx: 12px;
  cy: 7.25px;
  r: 4px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mqoc1vb-o {
  d: path("M5 20.25h14a1 1 0 0 0 1-1c0-3-3.6-5.25-8-5.25s-8 2.25-8 5.25a1 1 0 0 0 1 1");
}

</style>
