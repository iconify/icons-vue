<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l600e1ikp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tennis-court-grass" /></template>
<style>
.l600e1ikp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 2.5h11l4 10.5h-19Zm9 19q0-3-1.5-5.25m4.25 5.25v-5.75M21 21.5q0-3 1-5.25M4.5 7.75h15M12 2.5V13");
}

</style>
