<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e7fwg0z-n"/><path class="b9x-f2b8m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sort-reverse" /></template>
<style>
.b9x-f2b8m {
  d: path("M4.25 6.75L7.5 3.5l3.25 3.25m2.5 10.5l3.25 3.25l3.25-3.25");
}

.e7fwg0z-n {
  d: path("M7.5 3.5v6c0 2.5 9 2.5 9 5v6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
