<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="doa0urb5r"/><path class="v1sw4xe_d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:surgical-staples" /></template>
<style>
.doa0urb5r {
  d: path("M2.5 12c2.5-1 4.5 1 7 0s4.5 1 7 0c2-.75 3.5.5 5 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v1sw4xe_d {
  d: path("M4 15.5v-7h3.5v7m2.75 0v-7h3.5v7m2.75 0v-7H20v7");
}

</style>
