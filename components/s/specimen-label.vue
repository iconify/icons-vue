<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q8ovzjbcc"/><path class="fe_8vhw0j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:specimen-label" /></template>
<style>
.fe_8vhw0j {
  d: path("M5.75 12a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm4.75-3.5v7m2.5-7v7m2.5-7v7m2.5-7v7");
}

.q8ovzjbcc {
  d: path("M7.5 5h12c1.1 0 2 .9 2 2v10c0 1.1-.9 2-2 2h-12l-5-7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
