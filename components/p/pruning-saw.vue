<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="odeaol3md"/><path class="m8np6tuws"/><path class="pik8k5sre"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pruning-saw" /></template>
<style>
.m8np6tuws {
  d: path("m7.5 12.5l-5 4.5v3A1.5 1.5 0 0 0 4 21.5h5.5A1.5 1.5 0 0 0 11 20v-4.5");
}

.odeaol3md {
  d: path("M7.5 12.5q3.5-9 14-10l-1 3.25l-3 .5l-.5 3l-2.5.75l-.5 3.5l-3 2Z");
}

.pik8k5sre {
  d: path("M5.25 17.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
