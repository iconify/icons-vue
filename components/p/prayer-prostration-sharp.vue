<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="e6heisg1z"/><path class="ft_dr5bve"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:prayer-prostration-sharp" /></template>
<style>
.e6heisg1z {
  cx: 4.5px;
  cy: 19.5px;
  r: 1.75px;
}

.ft_dr5bve {
  d: path("m9 16.5l.5 4.75M9 16.5c2-3.25 4.5-5.25 8-5.5l-1.25 10.25m4.75 0V18.5M2.75 21.25h18.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
