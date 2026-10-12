<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="zhrmdpbwo"/><path class="kju4aacwz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:umbilical-clamp-sharp" /></template>
<style>
.kju4aacwz {
  d: path("m6.6 11.3l13.9-6.05M6.6 12.7l13.9 6.05M12 8.95l.6 1.38m3.9-3.34l.6 1.38M12 15.05l.6-1.38m3.9 3.34l.6-1.38");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zhrmdpbwo {
  cx: 5px;
  cy: 12px;
  r: 1.75px;
}

</style>
