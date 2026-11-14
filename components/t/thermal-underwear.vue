<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrtl8qbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:thermal-underwear" /></template>
<style>
.hrtl8qbmv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M21.077 12.902L19.75 4.75L15.5 3C15 4.75 13.75 5.75 12 5.75S9 4.75 8.5 3L4.25 4.75L2.5 15.5h3.25L7 10v11h6.122M17 12.178V10l.492 2.167M18 15v6m-2.5-4.5l5 3m-5 0l5-3");
}

</style>
