<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qum3ui5xk"/><path class="x8h3occ2f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:necklace-beads-ancient" /></template>
<style>
.qum3ui5xk {
  d: path("M4.5 4c0 9 3.5 13 7.5 13s7.5-4 7.5-13");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x8h3occ2f {
  d: path("M4.25 11a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm3 4a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm7 0a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm3-4a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0ZM12 17c1.5 1.5 2 2.25 2 3a2 2 0 0 1-4 0c0-.75.5-1.5 2-3Z");
}

</style>
