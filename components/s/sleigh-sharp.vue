<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="fvmu2wb8c"/><path class="jfom0db0e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sleigh-sharp" /></template>
<style>
.fvmu2wb8c {
  d: path("M2.75 7.25V6h3.5v5.25h9.7l.8-2l.5-1.25A2 2 0 0 1 21 9.25c-.5 4-3 6.5-6.5 6.5H2.75V13.5Z");
}

.jfom0db0e {
  d: path("M10.25 11.25h3V8.4l-1.5-.9l.5-1.25h-2l.5 1.25l-1.5.9v2.85zM6.75 16v4.25M14 16v4.25m-11.25 0H21V16.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
