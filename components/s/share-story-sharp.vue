<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="tqj6lmj3z"/><circle class="y56pw2b3p"/><circle class="i2799mjyd"/><path class="nh_j4ibuz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:share-story-sharp" /></template>
<style>
.i2799mjyd {
  cx: 17.5px;
  cy: 18.5px;
  r: 2.5px;
}

.nh_j4ibuz {
  d: path("m9.3 10.35l5.4-3.2m-5.4 6.5l5.4 3.2");
}

.tqj6lmj3z {
  cx: 17.5px;
  cy: 5.5px;
  r: 2.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y56pw2b3p {
  cx: 6.5px;
  cy: 12px;
  r: 2.5px;
}

</style>
