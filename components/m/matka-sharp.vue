<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="r9eu2imut"/><path class="hbwxprizm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:matka-sharp" /></template>
<style>
.hbwxprizm {
  d: path("M7 13.75c1.25-.8 2.5.8 3.75 0s2.5.8 3.75 0l1.563-1l.937 1");
}

.r9eu2imut {
  d: path("M9.75 3H15v1.5h-1.25v2.6c2.9.9 4.75 3.65 4.75 7.15c0 4.1-2.8 7-6.5 7s-6.5-2.9-6.5-7c0-3.5 1.85-6.25 4.75-7.15V4.5H9V3z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
