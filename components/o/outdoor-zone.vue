<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="degrfabdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:outdoor-zone" /></template>
<style>
.degrfabdj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 7V3h4m10 0h4v4m0 10v4h-4M7 21H3v-4m7.5-14h3m-3 18h3M3 10.5v3m18-3v3M12 6l4 8.5H8Zm0 8.5V18");
}

</style>
