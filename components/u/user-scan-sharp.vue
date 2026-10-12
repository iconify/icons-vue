<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="cey46ju5m"/><path class="pbwxvrb6w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:user-scan-sharp" /></template>
<style>
.cey46ju5m {
  cx: 12px;
  cy: 9px;
  r: 2.25px;
}

.pbwxvrb6w {
  d: path("M8.5 17.75H16v-.5c0-1.9-1.8-3.25-4-3.25s-4 1.35-4 3.25v.5zM3 7.5V3h4.5m9 0H21v4.5m0 9V21h-4.5m-9 0H3v-4.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
