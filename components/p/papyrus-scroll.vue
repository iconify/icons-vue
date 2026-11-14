<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahw-v2b2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:papyrus-scroll" /></template>
<style>
.ahw-v2b2s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 2.5h12.5A1.75 1.75 0 0 1 20 4.25A1.75 1.75 0 0 1 18.25 6H5.75A1.75 1.75 0 0 1 4 4.25A1.75 1.75 0 0 1 5.75 2.5m0 15.5h12.5A1.75 1.75 0 0 1 20 19.75a1.75 1.75 0 0 1-1.75 1.75H5.75A1.75 1.75 0 0 1 4 19.75A1.75 1.75 0 0 1 5.75 18M6.5 6v12m11-12v12m-8-6h5");
}

</style>
