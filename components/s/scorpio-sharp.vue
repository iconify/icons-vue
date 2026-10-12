<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="q40014x2y"/><path class="yslorpc4u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:scorpio-sharp" /></template>
<style>
.q40014x2y {
  d: path("M3.75 6.5H6v13.75M6 9V6.5h5v13.75M11 9V6.5h5v12h4.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yslorpc4u {
  d: path("m18.5 16.25l2.25 2.25l-2.25 2.25");
}

</style>
