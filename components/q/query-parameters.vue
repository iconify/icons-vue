<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lx0g_8jyc"/><path class="l7vvvke5b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:query-parameters" /></template>
<style>
.l7vvvke5b {
  d: path("M10 10.75h5v3.5h-5Zm7.25 1.75H18M6 16.75h7");
}

.lx0g_8jyc {
  d: path("M2.5 3.5h19v17h-19Zm0 4.5h19M6 12.5h1.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
