<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ttwykx09c"/><path class="xmbg2gbqc"/><path class="udhmxkbzi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shower-sharp" /></template>
<style>
.ttwykx09c {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 21.25v-14a4.5 4.5 0 0 1 9 0");
}

.udhmxkbzi {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.25 15.25h.01m2.99.5h.01m2.99-.5h.01m-4.51 4h.01m2.99 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.xmbg2gbqc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 11.75a4.5 4.5 0 0 1 9 0Z");
}

</style>
