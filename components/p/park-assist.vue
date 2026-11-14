<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gx77vdsar"/><path class="e2rr2ne1q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:park-assist" /></template>
<style>
.e2rr2ne1q {
  d: path("M8.5 7q3.5-1.5 7 0m-7 4.5q3.5 1.25 7 0m-1.379 6.121a3 3 0 0 1-4.242 0m5.978 2.475a6 6 0 0 1-7.714 0");
}

.gx77vdsar {
  d: path("M8.5 2.5h7v13h-7ZM4 2.5v19m16-19v19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
