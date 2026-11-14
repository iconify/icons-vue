<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l6oz-khek"/><path class="nqrh00bso"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:monitor-download" /></template>
<style>
.l6oz-khek {
  d: path("M2.5 3.5h19v13h-19Zm9.5 13v4m-4 0h8m-4-14V12");
}

.nqrh00bso {
  d: path("M9.75 9.75L12 12l2.25-2.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
