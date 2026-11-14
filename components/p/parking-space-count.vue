<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gzwzpibrh"/><path class="ngr8pmbps"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:parking-space-count" /></template>
<style>
.gzwzpibrh {
  d: path("M2.5 3h19v13h-19ZM12 16v5.5");
}

.ngr8pmbps {
  d: path("M6 13V6h2a2 2 0 0 1 0 4H6m7-3.5V13m2.5-5.25a1.75 1.75 0 0 1 3.5 0c0 2-3.5 3-3.5 5.25H19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
