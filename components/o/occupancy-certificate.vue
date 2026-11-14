<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pmzhhkmpk"/><path class="i7bi7hbey"/><path class="s6j3xwxah"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:occupancy-certificate" /></template>
<style>
.i7bi7hbey {
  d: path("M14.75 21.75v-7.5H21v7.5");
}

.pmzhhkmpk {
  d: path("M11.9 18H2.5V3.5h19v7.9M6 7.5h12M6 11h5.9");
}

.s6j3xwxah {
  d: path("m14.75 14.25l3.5 1.25v6.25h-3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
