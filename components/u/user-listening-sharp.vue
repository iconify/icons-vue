<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="qexqi5bar"/><path class="n19m9rqdm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:user-listening-sharp" /></template>
<style>
.n19m9rqdm {
  d: path("M6 21.25h12.75v-.75c0-2.6-3.02-4.5-6.75-4.5s-6.75 1.9-6.75 4.5v.75zM4.5 9a7.5 6 0 0 1 15 0M3 9h3v4.5H3zm15 0h3v4.5h-3z");
}

.qexqi5bar {
  cx: 12px;
  cy: 9.5px;
  r: 3px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
