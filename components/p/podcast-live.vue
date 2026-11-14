<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eg635ud8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:podcast-live" /></template>
<style>
.eg635ud8n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5za3 3 0 0 1 3 3v4a3 3 0 0 1-3 3a3 3 0 0 1-3-3v-4a3 3 0 0 1 3-3m0 10v9m-3.5 0h7M17.25 3a7 7 0 0 1 0 9M6.75 3a7 7 0 0 0 0 9M20.5 2.5a10 10 0 0 1 0 10m-17-10a10 10 0 0 0 0 10");
}

</style>
