<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="af5o1nbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tournament-bracket-sharp" /></template>
<style>
.af5o1nbfu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4.5h5.5V10h-5.5m0 4h5.5v5.5h-5.5m5.5-12.25h4.5v9.5h-4.5m4.5-4.75h2m4.15-1.93l.41.89l.15.32l.34.04l.98.12l.35.04l-.26.24l-.72.66l-.26.24l.07.34l.19.97l.07.34l-.31-.17l-.85-.48l-.31-.17l-.31.17l-.85.48l-.31.17l.07-.34l.19-.97l.07-.34l-.26-.24l-.72-.66l-.26-.24l.35-.04l.98-.12l.34-.04l.15-.32l.41-.89l.15-.32z");
}

</style>
