<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o0uxpabcc"/><path class="q7b8ccbmt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mask-sky" /></template>
<style>
.o0uxpabcc {
  d: path("M2.5 3.5h19v17h-19Z");
}

.q7b8ccbmt {
  d: path("M2.5 16c3.5-2.5 6.5 2.5 10 0s6 1 9-1m-12-3.25a2 2 0 0 1-.25-4a2.75 2.75 0 0 1 5 .5a1.75 1.75 0 0 1 .25 3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
