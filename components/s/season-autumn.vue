<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lu1q29k_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:season-autumn" /></template>
<style>
.lu1q29k_s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 10v2c0 5 3 8 5.5 9.5c2.5-1.5 5.5-4.5 5.5-9.5v-2m-13 0h15c0-4-3.5-5.5-7.5-5.5S4.5 6 4.5 10ZM12 4.5c0-1.25.75-2 2-2");
}

</style>
