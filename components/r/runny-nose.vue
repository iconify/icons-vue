<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="aszq1ab4h"/><path class="gjcrqmbnl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:runny-nose" /></template>
<style>
.aszq1ab4h {
  d: path("M10.75 3c0 4-1.25 6.5-2.75 8.5c-1.25 1.5-.75 4 1.25 4c.75 0 1.25.75 2.75.75s2-.75 2.75-.75c2 0 2.5-2.5 1.25-4c-1.5-2-2.75-4.5-2.75-8.5");
}

.gjcrqmbnl {
  fill: currentColor;
  d: path("M9.25 17.5c1 1.25 1.5 2 1.5 2.75s-.65 1.25-1.5 1.25s-1.5-.5-1.5-1.25s.5-1.5 1.5-2.75Zm5.5 0c1 1.25 1.5 2 1.5 2.75s-.65 1.25-1.5 1.25s-1.5-.5-1.5-1.25s.5-1.5 1.5-2.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
