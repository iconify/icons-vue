<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="sy-danb0p"/><path class="w515kd1fk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:swimsuit-sharp" /></template>
<style>
.sy-danb0p {
  d: path("M7.5 2.75H9q.75 4.5 3 4.5c2.25 0 2.5-1.5 3-4.5h1.5c0 3.5 1.25 5.5 1.25 8.5c0 2.5-1 4-1 6c-2 0-3.25 1.25-4 3.75h-1.5c-.75-2.5-2-3.75-4-3.75c0-2-1-3.5-1-6c0-3 1.25-5 1.25-8.5Z");
}

.w515kd1fk {
  d: path("M6.75 13c3.25.75 7.25.75 10.5 0");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
