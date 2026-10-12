<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wjs5id0jz"/><path class="j9ip8fbfi"/><path class="g0yjewmrh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shopping-mall" /></template>
<style>
.g0yjewmrh {
  d: path("M10.25 13.75a1.75 1.75 0 0 0 3.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j9ip8fbfi {
  d: path("M9.5 11.5h5q1 0 1.07 1l.36 5.25q.07 1-.93 1H9q-1 0-.93-1l.36-5.25q.07-1 1.07-1");
}

.wjs5id0jz {
  d: path("M2.75 19.75V11.5q0-1.5 1.36-2.13l6.53-2.99q1.36-.63 2.72 0l6.53 2.99q1.36.63 1.36 2.13v8.25q0 1.5-1.5 1.5H4.25q-1.5 0-1.5-1.5");
}

</style>
