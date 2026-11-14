<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k2q427bcm"/><path class="llziffb6b"/><path class="gtg72fbwi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pipeline-run" /></template>
<style>
.gtg72fbwi {
  d: path("m15 14.5l6.5 3.5l-6.5 3.5Z");
}

.k2q427bcm {
  d: path("M5.75 5H3.5A1.5 1.5 0 0 0 2 6.5v3A1.5 1.5 0 0 0 3.5 11h2.25m3.5-6h2.5m-2.5 6h2.5m3.5-6h5.25A1.5 1.5 0 0 1 22 6.5v3a1.5 1.5 0 0 1-1.5 1.5h-5.25");
}

.llziffb6b {
  fill: currentColor;
  d: path("M6.75 3h1.5v10h-1.5Zm6 7.1V3h1.5v7.9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
