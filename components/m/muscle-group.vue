<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="no92k1blf"/><path class="h56c3lwoj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:muscle-group" /></template>
<style>
.h56c3lwoj {
  d: path("M13 16.5q2.5-2 5-.5");
}

.no92k1blf {
  d: path("M21 21.5H6.5c-3 0-3.5-2.5-2.5-5L7 6c.5-2 2-3 4-3h2.5c1.5 0 2 1.5 1 2.5l-3 2l-2 5.5c2.5-2.5 7.5-3 9.5-.5c1.5 1.5 2 3 2 4.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
