<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gepfux8ew"/><path class="zq0zm5bed"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wash-60" /></template>
<style>
.gepfux8ew {
  d: path("M3 7q2.25-2 4.5 0T12 7t4.5 0T21 7l-2.25 11.5H5.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zq0zm5bed {
  d: path("M6.5 12.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm4.5 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm4.5 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

</style>
