<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlm9_vbqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-insurance" /></template>
<style>
.vlm9_vbqp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12a9.5 9 0 0 1 19 0c-1.5-1.5-4.75-1.5-6.25 0c-1.5-1.5-5-1.5-6.5 0c-1.5-1.5-4.75-1.5-6.25 0Zm9.5 0v6.5a2 2 0 0 1-4 0");
}

</style>
