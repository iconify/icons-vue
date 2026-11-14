<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f2_cpgbgs"/><path class="pb7u_ccsx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:scoop-bin" /></template>
<style>
.f2_cpgbgs {
  d: path("M2.5 10h15L16 21.5H4Zm0-2L4 2.5h7L10 8Zm.75 6h13.5");
}

.pb7u_ccsx {
  d: path("M6 14a2.5 2 0 0 0 5 0m0 0l8.5-7m-13 11h1m3 .5h1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
