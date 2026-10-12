<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dg-fj1b0z"/><path class="jg0aywb6k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:training-loop-sharp" /></template>
<style>
.dg-fj1b0z {
  d: path("M19.4 10.5A7.5 7.5 0 0 0 5.5 8.25m0-3.75v3.75h3.75M4.6 13.5a7.5 7.5 0 0 0 13.9 2.25m0 3.75v-3.75h-3.75");
}

.jg0aywb6k {
  d: path("M12 8.5q.42 3.08 3.5 3.5q-3.08.42-3.5 3.5q-.42-3.08-3.5-3.5q3.08-.42 3.5-3.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
