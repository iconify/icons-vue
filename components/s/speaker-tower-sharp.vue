<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ojcyq51dz"/><circle class="p98yu_b-b"/><circle class="nxcjk5gco"/><path class="nbwtimgyq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:speaker-tower-sharp" /></template>
<style>
.nbwtimgyq {
  d: path("M8.75 19.25v2m6.5-2v2");
}

.nxcjk5gco {
  cx: 12px;
  cy: 14px;
  r: 1.75px;
}

.ojcyq51dz {
  d: path("M7 2.75h10v16.5H7z");
}

.p98yu_b-b {
  cx: 12px;
  cy: 7.75px;
  r: 1.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
