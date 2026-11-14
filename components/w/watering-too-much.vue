<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pxnv1wzgl"/><path class="wu13l-5vt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:watering-too-much" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pxnv1wzgl {
  d: path("M6 10.5h12l-1.5 6.75h-9Zm6 0V7m0 .5c-2.5 0-4.5-1.5-4.5-4C10 3.5 12 5 12 7.5m0-.5c0-2.5 2-4 4.5-4c0 2.5-2 4-4.5 4");
}

.wu13l-5vt {
  d: path("M2.5 14q2.5-1.5 5 0t5 0t5 0t4 0M3 20.75q2.5-1.25 5 0t5 0t5 0t3 0");
}

</style>
