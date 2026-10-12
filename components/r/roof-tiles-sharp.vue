<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="pyp7xmbpk"/><path class="rvl38lbbw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:roof-tiles-sharp" /></template>
<style>
.pyp7xmbpk {
  d: path("M8.25 4.75h13l-5.5 12.75a1.63 1.63 0 0 1-3.25 0a1.63 1.63 0 0 1-3.25 0a1.63 1.63 0 0 1-3.25 0a1.63 1.63 0 0 1-3.25 0Z");
}

.rvl38lbbw {
  d: path("M5.55 11h2.3a1.4 1.4 0 0 0 2.8 0a1.4 1.4 0 0 0 2.8 0a1.4 1.4 0 0 0 2.8 0h2.3");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
