<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsohwnqyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:road-unpaved" /></template>
<style>
.nsohwnqyx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 21.5l2-4.5l-.75-3l2-4.5l-.5-3L8 2.5m12.5 19l-2-4.5l.75-3l-2-4.5l.5-3l-1.75-4M11 7h.01M13 12h.01M11 17h.01");
}

</style>
