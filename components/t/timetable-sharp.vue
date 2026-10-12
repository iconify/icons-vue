<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="bl4abfb3f"/><path class="gq9a447ri"/><path class="d0l1tlnzg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:timetable-sharp" /></template>
<style>
.bl4abfb3f {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h18.5v18.5H2.75zm0 6.25h18.5m-18.5 6h18.5");
}

.d0l1tlnzg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 5.88h8m-8 6.12h5m-5 6.13h8");
}

.gq9a447ri {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.75 5.88h.01M5.75 12h.01m-.01 6.13h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
