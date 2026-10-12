<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="q7xsvn27y"/><path class="n35_wj4xu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:resort-sharp" /></template>
<style>
.n35_wj4xu {
  d: path("M10.5 15.25V12h3v3.25m-5.75 0v3.5m8.5-3.5v3.5M2.75 20.5L5.06 19l2.31 1.5l2.315 1.503L12 20.5l2.308-1.498L16.63 20.5l2.317 1.495L21.25 20.5");
}

.q7xsvn27y {
  d: path("m3.55 9.65l7.65-5.8l.8-.6l.8.6l7.65 5.8l.8.6H18.5v5h-13v-5H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
