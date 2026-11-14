<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wu2bw56kj"/><path class="h-98b_owd"/><path class="zebutmbne"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:standard-certified" /></template>
<style>
.h-98b_owd {
  d: path("M6.5 15.5a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wu2bw56kj {
  d: path("M6.5 3h3.75L12 6.5L13.75 3h3.75l-3.25 7h-4.5Z");
}

.zebutmbne {
  d: path("m9.75 15.5l1.75 1.75l3-3.25");
}

</style>
