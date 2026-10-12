<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rp5yppd8x"/><path class="c4frs250p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:recliner-sharp" /></template>
<style>
.c4frs250p {
  d: path("m16.9 13.63l2.7-1.51l.65-.37l.34.67l.32.66l.34.67l-.63.41l-3.74 2.43l-.63.41v-3z");
}

.rp5yppd8x {
  d: path("m3.66 4.34l.93-.43l.91-.41l.41.91l2.93 6.43l.41.91h-3.5l-.39-.92l-2.22-5.16l-.39-.92zm1.59 7.41h11v9.5h-11zm0 3.5h11");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
