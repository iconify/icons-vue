<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jdmcpsh9z"/><path class="pudody9mo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-university" /></template>
<style>
.jdmcpsh9z {
  d: path("m3 9.5l9-4.25l9 4.25l-9 4.25Z");
}

.pudody9mo {
  d: path("M6.75 11.25v5.25c0 1.5 2.25 3 5.25 3s5.25-1.5 5.25-3v-5.25M21 9.5v6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
