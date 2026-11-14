<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xrdj63b2s"/><path class="v4z03ubam"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:photo-booth-frame" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v4z03ubam {
  d: path("M10 8a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-2.5 8.5c0-2.75 2-3.75 4.5-3.75s4.5 1 4.5 3.75");
}

.xrdj63b2s {
  d: path("M4 2.5h16v14H4Zm6.5 14v4a1 1 0 0 0 1 1h1a1 1 0 0 0 1-1v-4");
}

</style>
