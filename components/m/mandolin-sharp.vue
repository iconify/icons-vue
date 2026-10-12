<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="mh9zuwmmp"/><circle class="l888ssy_d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mandolin-sharp" /></template>
<style>
.l888ssy_d {
  cx: 12px;
  cy: 15.75px;
  r: 1.75px;
}

.mh9zuwmmp {
  d: path("M12 8.5c2 1.5 6.25 3.6 6.25 7.6c0 3.2-2.8 5.15-6.25 5.15S5.75 19.3 5.75 16.1c0-4 4.25-6.1 6.25-7.6Zm0 0V6m-2-3.25h4V6h-4z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
