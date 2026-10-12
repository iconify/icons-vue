<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pq-5m64_d"/><path class="ik9_4vsqt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:welding-torch" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ik9_4vsqt {
  d: path("M10.9 18.5Q8 21.25 2.75 21m12.65-7l1.5-1.5q1.75-1.75 1.75-2.75m-1.4-3c0-1.75.75-3 1.4-4c.65 1 1.4 2.25 1.4 4Z");
}

.pq-5m64_d {
  d: path("m10.19 16.03l2.74-2.74q.88-.88 1.76 0l1.42 1.42q.88.88 0 1.76l-2.74 2.74q-.88.88-1.76 0l-1.42-1.42q-.88-.88 0-1.76");
}

</style>
