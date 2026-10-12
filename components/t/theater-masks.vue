<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yk971xbcb"/><path class="wgd7bnzdy"/><path class="l04167bfs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:theater-masks" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l04167bfs {
  d: path("m14.75 13.25l1.75.75m1.75 0l1.75-.75M15.25 18c1.25-1.5 3-1.5 4.25 0");
}

.wgd7bnzdy {
  d: path("M4.25 7.5q.9-1.1 1.75 0m1.25 0q.9-1.1 1.75 0m-4.5 2.75c1.25 1.5 3 1.5 4.25 0m4.75.25q3.875-1.5 7.75 0v5c0 3-1.937 5-3.875 5s-3.875-2-3.875-5Z");
}

.yk971xbcb {
  d: path("M2.75 4q3.875-1.5 7.75 0v5c0 3-1.937 5-3.875 5S2.75 12 2.75 9Z");
}

</style>
