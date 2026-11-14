<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2yyomfcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:player-tracking" /></template>
<style>
.a2yyomfcq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM3 20.5c0-4 3.5-6.5 8-6.5c.933 0 1.823.107 2.647.313M18.5 21.75C16.75 20 15.75 18.5 15.75 17a2.75 2.75 0 0 1 5.5 0c0 1.5-1 3-2.75 4.75Z");
}

</style>
