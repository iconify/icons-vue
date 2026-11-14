<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8-remb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:map-check" /></template>
<style>
.s8-remb1k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.138 19.308L9 18l-6 2.5V6l6-2.5L15 6l6-2.5v8.3M9 3.5V18m6-12v3.25M14.75 18l2 2L21 15.75");
}

</style>
