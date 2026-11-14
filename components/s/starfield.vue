<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j_psw1y4g"/><path class="p5o4pdbkp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:starfield" /></template>
<style>
.j_psw1y4g {
  d: path("M3 3h18v18H3Z");
}

.p5o4pdbkp {
  d: path("m14 6l1 3l3 1l-3 1l-1 3l-1-3l-3-1l3-1ZM7.5 7.5h.01m-.51 8a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm9.5 1.5h.01m-4.51.75h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
