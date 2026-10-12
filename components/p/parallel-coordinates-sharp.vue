<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="myvl9cblf"/><path class="ogabaqb3s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:parallel-coordinates-sharp" /></template>
<style>
.myvl9cblf {
  d: path("M4 4v16m8-16v16m8-16v16M4 7l8 8l8-6");
}

.ogabaqb3s {
  d: path("m4 16l8-9l8 8");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
