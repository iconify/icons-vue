<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zo56sezxh"/><path class="yks8e7b7q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ringette-ring" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yks8e7b7q {
  d: path("M7 15a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM20.5 2.5l-8 9");
}

.zo56sezxh {
  d: path("M4 15a5 5 0 1 0 10 0a5 5 0 1 0-10 0Z");
}

</style>
