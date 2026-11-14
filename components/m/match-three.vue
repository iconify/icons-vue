<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rda_n06uy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:match-three" /></template>
<style>
.rda_n06uy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 7.5h2.5L7 10l-2.5 6.5L2 10ZM2 10h5m3.75-2.5h2.5L14.5 10L12 16.5L9.5 10ZM9.5 10h5m3.75-2.5h2.5L22 10l-2.5 6.5L17 10ZM17 10h5");
}

</style>
