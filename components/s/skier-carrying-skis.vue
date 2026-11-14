<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="no9jhb0mh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:skier-carrying-skis" /></template>
<style>
.no9jhb0mh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 7a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM2.5 21.5C2.5 17.5 5 15 8 15s5.5 2.5 5.5 6.5m3.25 0L14.5 4.75q-.25-2.25 1.5-2m4.75 18.75L18.5 4.75q-.25-2.25 1.5-2");
}

</style>
