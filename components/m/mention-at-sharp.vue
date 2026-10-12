<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vgu78uopy"/><circle class="yvz9c8brq"/><path class="znvvjn38k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mention-at-sharp" /></template>
<style>
.vgu78uopy {
  d: path("M2.75 6.25v-2.5h18.5v14H12.5L8 20.85l-1.25 1v-4.1h-4v-2.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yvz9c8brq {
  cx: 12px;
  cy: 10.75px;
  r: 1.75px;
}

.znvvjn38k {
  d: path("M13.75 9v3.5h2.5v-1.75a4.25 4.25 0 1 0-1.75 3.45");
}

</style>
