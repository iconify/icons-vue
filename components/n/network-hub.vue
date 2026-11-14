<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b5nepebom"/><path class="avis6_bfg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:network-hub" /></template>
<style>
.avis6_bfg {
  d: path("M5.25 12h1.5v1.5h-1.5Zm4 0h1.5v1.5h-1.5Zm4 0h1.5v1.5h-1.5Zm4 0h1.5v1.5h-1.5Z");
}

.b5nepebom {
  d: path("M2.5 7h19v10h-19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
