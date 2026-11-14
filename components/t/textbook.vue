<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0vs3vbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:textbook" /></template>
<style>
.b0vs3vbmd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 18.5V5a2 2 0 0 1 2-2h12v13.5H7a2 2 0 0 0 0 4h12m-9.5-13h6m-6 3.5h4");
}

</style>
