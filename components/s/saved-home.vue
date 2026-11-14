<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ylxmw6bsr"/><path class="x5x2yzq_r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:saved-home" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x5x2yzq_r {
  d: path("M8.5 10L12 6.5l3.5 3.5v3.5h-7Z");
}

.ylxmw6bsr {
  d: path("M5.5 4.5a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v17l-6.5-5l-6.5 5Z");
}

</style>
