<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="il28g3_yv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:microscope-camera" /></template>
<style>
.il28g3_yv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 2.5H14v5H4.5Zm2.5 5h4.5V14H7Zm4.5 3c5 0 7 4.5 4 7.5v2.5M5 17h7.5M5 20.5h14");
}

</style>
