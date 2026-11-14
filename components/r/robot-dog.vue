<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cijxft70z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:robot-dog" /></template>
<style>
.cijxft70z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11.5A1.5 1.5 0 0 1 4 10h10.5V5.5a1 1 0 0 1 1-1h5a1 1 0 0 1 1 1V10a1 1 0 0 1-1 1h-3v4a1.5 1.5 0 0 1-1.5 1.5H4A1.5 1.5 0 0 1 2.5 15Zm14-7V2M5 16.5V21m3.5-4.5V21m3.5-4.5V21m3.5-4.5V21m3-13.5h.01");
}

</style>
