<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ugi0fhtsy"/><path class="v-9oxlbsp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:twist-tie" /></template>
<style>
.ugi0fhtsy {
  d: path("M10.5 12c-5.5 1-7 4-7 6.5c0 2 1.5 3 3.5 3h10c2 0 3.5-1 3.5-3c0-2.5-1.5-5.5-7-6.5m-3-2.5l-2-4h7l-2 4m-4 0h5V12h-5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v-9oxlbsp {
  d: path("M14.5 10.75c2 0 3-1.5 2.25-2.5c-.5-.5-1.25-.25-1.25.5m-6 2c-2 0-3-1.5-2.25-2.5c.5-.5 1.25-.25 1.25.5");
}

</style>
