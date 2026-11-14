<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sdwwkhwzs"/><path class="p4fyhup8c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:nebula" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p4fyhup8c {
  d: path("M12 10q.5 2 2.5 2.5q-2 .5-2.5 2.5q-.5-2-2.5-2.5q2-.5 2.5-2.5");
}

.sdwwkhwzs {
  d: path("M5 15.5C2 15 2 9.5 6 9c.5-4 6-5.5 8.5-2.5c3-1.5 7 1 5.5 4.5c2.5 2.5 1 7.5-3 7c-2 3-7.5 3-8.5 0c-2 .5-3.5-.5-3.5-2.5");
}

</style>
