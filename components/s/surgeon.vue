<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fca6_cbht"/><path class="pyhjqqe3b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:surgeon" /></template>
<style>
.fca6_cbht {
  d: path("M4 20c0-3.25 3.5-5.5 8-5.5s8 2.25 8 5.5c0 .6-.4 1-1 1H5c-.6 0-1-.4-1-1ZM16.5 8a4.5 4.5 0 0 1-9 0m0 0c0-3.25 2-5.25 4.5-5.25s4.5 2 4.5 5.25Z");
}

.pyhjqqe3b {
  d: path("M9.25 9.5h5.5v3h-5.5Zm0 .5l-1.5-1m7 1l1.5-1m-6.5 5.75L12 18l2.25-3.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
