<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ciqzjkbdd"/><path class="twrukjbio"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:safety-pin-sharp" /></template>
<style>
.ciqzjkbdd {
  d: path("M2.75 13a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

.twrukjbio {
  d: path("M5 10.75h11.25M5 15.25h11.5l2-2M16.25 9h5v3.5h-5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
