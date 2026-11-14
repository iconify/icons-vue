<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdxlpnbwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:server-off" /></template>
<style>
.cdxlpnbwt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.4 3.5H21v7h-6.6m-7.8 0H3V6.9m13.6 13.6H3v-7h6.6m7.8 0H21v3.6M6.75 17h.01M11.5 7h6m-6 10h1.6M3.5 3.5l17 17");
}

</style>
