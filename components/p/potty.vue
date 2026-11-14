<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b54s01gew"/><path class="ykf7wvbxl"/><path class="wl7q-acqt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:potty" /></template>
<style>
.b54s01gew {
  d: path("M6 9.25v-4a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wl7q-acqt {
  d: path("M5 11.75c.5 5 3 6.5 7 6.5s6.5-1.5 7-6.5m-11.5 6.5h9v2.5h-9Z");
}

.ykf7wvbxl {
  d: path("M4 10.75a8 2.25 0 1 0 16 0a8 2.25 0 1 0-16 0Z");
}

</style>
