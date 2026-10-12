<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="e9-7-8-2z"/><path class="y34z99ejm"/><path class="keqspgbaa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:meditation" /></template>
<style>
.e9-7-8-2z {
  cx: 12px;
  cy: 4.75px;
  r: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.keqspgbaa {
  d: path("M2.75 18.5c0-1.75 1.75-3 4-3h10.5c2.25 0 4 1.25 4 3s-1.75 2.75-4 2.75H6.75c-2.25 0-4-1-4-2.75m5.5 0h7.5");
}

.y34z99ejm {
  d: path("M11.25 9h1.5q1.5 0 1.84 1.46l.82 3.58q.34 1.46-1.16 1.46h-4.5q-1.5 0-1.16-1.46l.82-3.58Q9.75 9 11.25 9M9.5 10l-3 2.75L4.75 16m9.75-6l3 2.75L19.25 16");
}

</style>
