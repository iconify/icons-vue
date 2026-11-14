<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r2e28kmgd"/><path class="vixm4xbmj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:swimmer-medal" /></template>
<style>
.r2e28kmgd {
  d: path("M6 15a6 6 0 1 0 12 0a6 6 0 1 0-12 0Zm.5-12.5L10 9.25m7.5-6.75L14 9.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vixm4xbmj {
  d: path("M8.75 15.5c1-1.25 2-1.25 3.25 0s2.25 1.25 3.25 0");
}

</style>
