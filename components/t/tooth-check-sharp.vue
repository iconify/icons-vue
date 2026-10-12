<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="b1w_gfikn"/><path class="z7z1zfbbk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tooth-check-sharp" /></template>
<style>
.b1w_gfikn {
  d: path("M7.5 3.25c-2.6 0-4.25 2.1-4.25 4.75c0 2.4 1 4 1.75 6.25c.7 2.1.9 7 3 7c1.9 0 1.6-5.25 4-5.25s2.1 5.25 4 5.25c2.1 0 2.3-4.9 3-7C19.75 12 20.75 10.4 20.75 8c0-2.65-1.65-4.75-4.25-4.75c-1.9 0-2.7 1-4.5 1s-2.6-1-4.5-1Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z7z1zfbbk {
  d: path("M7.5 6.75L5.915 7L5.75 8.65");
}

</style>
