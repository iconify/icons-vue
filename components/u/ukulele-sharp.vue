<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="wn7q51bhl"/><circle class="xbakwn5ni"/><path class="mej7q9r2w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ukulele-sharp" /></template>
<style>
.mej7q9r2w {
  d: path("M10.5 18.25h3");
}

.wn7q51bhl {
  d: path("M14.4 12.94a4.5 4.5 0 1 1-4.8 0a3.25 3.25 0 1 1 4.8 0ZM12 7.5V5.25m-1.75-2.5h3.5v2.5h-3.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xbakwn5ni {
  cx: 12px;
  cy: 13.5px;
  r: 1.5px;
}

</style>
