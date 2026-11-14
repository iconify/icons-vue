<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aszq1ab4h"/><path class="xumm34bha"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:runny-nose" /></template>
<style>
.aszq1ab4h {
  d: path("M10.75 3c0 4-1.25 6.5-2.75 8.5c-1.25 1.5-.75 4 1.25 4c.75 0 1.25.75 2.75.75s2-.75 2.75-.75c2 0 2.5-2.5 1.25-4c-1.5-2-2.75-4.5-2.75-8.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xumm34bha {
  fill: currentColor;
  d: path("M9.25 17.5c1 1.25 1.5 2 1.5 2.75s-.65 1.25-1.5 1.25s-1.5-.5-1.5-1.25s.5-1.5 1.5-2.75m5.5 0c1 1.25 1.5 2 1.5 2.75s-.65 1.25-1.5 1.25s-1.5-.5-1.5-1.25s.5-1.5 1.5-2.75");
}

</style>
