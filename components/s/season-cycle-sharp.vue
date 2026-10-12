<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zpnpfkblo"/><path class="fvdas8ylf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:season-cycle-sharp" /></template>
<style>
.fvdas8ylf {
  d: path("M8.75 15.25c0-4.25 2.25-6.5 6.5-6.5c0 4.25-2.25 6.5-6.5 6.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zpnpfkblo {
  d: path("M4.01 9.09a8.5 8.5 0 0 1 15.98 0m-2.04-.95l2.04.95l.95-2.04m-.95 7.86a8.5 8.5 0 0 1-15.98 0m2.04.95l-2.04-.95l-.95 2.04");
}

</style>
