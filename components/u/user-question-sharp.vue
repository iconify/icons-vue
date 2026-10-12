<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="g2orrxpuo"/><path class="qdqmwzcrt"/><path class="rpwo-dbgz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:user-question-sharp" /></template>
<style>
.g2orrxpuo {
  cx: 9.5px;
  cy: 7.75px;
  r: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qdqmwzcrt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 20.25h11.75v-.75c0-3-2.8-5.25-6.25-5.25S3.25 16.5 3.25 19.5v.75zM16.25 8.5A2 2 0 1 1 19 10.35l-1 .417V12");
}

.rpwo-dbgz {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 14.25h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
