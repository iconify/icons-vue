<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pymc8tbrh"/><path class="uqvlqw35s"/><path class="wmth3xbmo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:overview-panel" /></template>
<style>
.pymc8tbrh {
  d: path("M2 3h20v18H2Zm0 5h20M4.75 5.5H9.5M8.75 8v13m6.5-13v13M4.5 17.5v-3m2.25 3V12");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uqvlqw35s {
  fill: currentColor;
  d: path("M10.75 13.75h2.5v2.5h-2.5Z");
}

.wmth3xbmo {
  d: path("m17 17l1.25-3l1.5 1.25l.5-2.75");
}

</style>
