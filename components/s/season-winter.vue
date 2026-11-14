<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sd8t7ccfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:season-winter" /></template>
<style>
.sd8t7ccfb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5v19M3.75 7.25l16.5 9.5m-16.5 0l16.5-9.5M9.5 3.5L12 6l2.5-2.5m3.5 2L17.25 9l3.25 1m0 4l-3.25 1l.75 3.5m-3.5 2L12 18l-2.5 2.5m-3.5-2l.75-3.5l-3.25-1m0-4l3.25-1L6 5.5");
}

</style>
