<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f3ydq3xpg"/><path class="t63tbub5x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stereo-pair" /></template>
<style>
.f3ydq3xpg {
  d: path("M2.5 5h8v11h-8Zm11 3h8v11h-8Z");
}

.t63tbub5x {
  d: path("M2.5 13.5L6 10l4.5 4m3 2.5L17 13l4.5 4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
