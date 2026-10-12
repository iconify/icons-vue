<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="c3f_17idn"/><circle class="svx1ycb0c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:vacuum-cleaner-sharp" /></template>
<style>
.c3f_17idn {
  d: path("M9.5 2.75L6 18.25m-3.25 0h7v3h-7zM8.88 5.5C12.5 5.5 14 8 14 12.25m-.75 0h8v9h-9.5v-9z");
}

.svx1ycb0c {
  cx: 16.5px;
  cy: 16.75px;
  r: 2px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
