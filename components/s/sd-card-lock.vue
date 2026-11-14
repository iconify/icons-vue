<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p1ukvsbes"/><path class="jljxofb7w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sd-card-lock" /></template>
<style>
.jljxofb7w {
  d: path("M9.75 14.5h4.5V18h-4.5Zm1 0v-1a1.25 1.25 0 0 1 2.5 0v1");
}

.p1ukvsbes {
  d: path("M9 2.5h8a2 2 0 0 1 2 2v15a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2v-13Zm1 4v3m3-3v3m3-3v3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
