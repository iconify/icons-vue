<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myn79m-iq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:snifter" /></template>
<style>
.myn79m-iq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 4h7c0 2 3.5 4 3.5 8a7 7 0 0 1-14 0c0-4 3.5-6 3.5-8ZM12 19v2m-3.5 0h7");
}

</style>
