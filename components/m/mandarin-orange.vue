<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ai_lqu7rh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mandarin-orange" /></template>
<style>
.ai_lqu7rh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 13.75a7.75 7.75 0 1 0 15.5 0a7.75 7.75 0 1 0-15.5 0ZM12 6V2.5m0 1C10.5 2 8 2 6 3c2 1.25 4.5 1.5 6 .5Z");
}

</style>
