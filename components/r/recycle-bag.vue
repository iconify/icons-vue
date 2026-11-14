<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e-eit08yd"/><path class="bwz-puxhk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:recycle-bag" /></template>
<style>
.bwz-puxhk {
  d: path("m9 16.5l2.25-3.75M10 13l1.25-.25l.25 1.25m1.25-1.25L15 16.5m.25-1.25L15 16.5l-1.25-.25m.5 1.25h-4.5m1-1l-1 1l1 1");
}

.e-eit08yd {
  d: path("M4 7h16l-1 14H5Zm4.5 0a3.5 3.5 0 0 1 7 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
