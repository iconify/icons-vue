<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="n8nhn6p-f"/><path class="sq82d72lh"/><path class="wr0qklbqh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:smart-home" /></template>
<style>
.n8nhn6p-f {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 9.75L12 3.25l8.25 6.5v8.5a2 2 0 0 1-2 2H5.75a2 2 0 0 1-2-2Z");
}

.sq82d72lh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 12.5h4.5a2.25 2.25 0 0 1 0 4.5h-4.5a2.25 2.25 0 0 1 0-4.5");
}

.wr0qklbqh {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.25 14.75h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
