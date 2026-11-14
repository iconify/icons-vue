<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o9978pbip"/><path class="j7l756bkd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:repeat-daily" /></template>
<style>
.j7l756bkd {
  d: path("M15.75 8.75L18 11l2.25-2.25m-4 9.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM18 14v1m0 6v1m-4-4h1m6 0h1");
}

.o9978pbip {
  d: path("M10.75 18A7.25 7.25 0 1 1 18 10.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
