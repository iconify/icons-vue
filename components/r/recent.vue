<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vyt9i_-zs"/><path class="ofy07xbzb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:recent" /></template>
<style>
.ofy07xbzb {
  d: path("M6 3v3h3m3 1.5V12l3 2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vyt9i_-zs {
  d: path("M3.5 12A8.5 8.5 0 1 0 6 6");
}

</style>
