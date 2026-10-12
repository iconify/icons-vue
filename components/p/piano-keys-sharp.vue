<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="fzg-nyb4e"/><path class="tyi7-kv0x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:piano-keys-sharp" /></template>
<style>
.fzg-nyb4e {
  d: path("M3 6h18v12H3z");
}

.tyi7-kv0x {
  d: path("M7.75 6h2.5v7h-2.5zm6 0h2.5v7h-2.5zM9 16v2m6-2v2");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
