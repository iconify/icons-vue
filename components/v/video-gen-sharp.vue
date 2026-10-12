<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="mxt2a2b3t"/><path class="mjl-2abua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:video-gen-sharp" /></template>
<style>
.mjl-2abua {
  d: path("M8.75 8.5q.42 3.08 3.5 3.5q-3.08.42-3.5 3.5q-.42-3.08-3.5-3.5q3.08-.42 3.5-3.5Z");
}

.mxt2a2b3t {
  d: path("M2.75 6h12v12h-12zm15.61 3.81l2.28-1.62l.61-.44v8.5l-.61-.44l-2.28-1.62l-.61-.44v-3.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
