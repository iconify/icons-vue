<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbov1ob_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:waiting-room" /></template>
<style>
.vbov1ob_c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 15.5h19M3 3.5h4.5V10H3Zm6.75 0h4.5V10h-4.5Zm6.75 0H21V10h-4.5ZM2.5 11H8v2H2.5Zm6.75 0h5.5v2h-5.5ZM16 11h5.5v2H16ZM4 15.5l-.5 5m8.5-5v5m8-5l.5 5");
}

</style>
