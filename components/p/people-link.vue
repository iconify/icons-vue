<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n7kl8ubds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:people-link" /></template>
<style>
.n7kl8ubds {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.563 20.5H3.5c-.6 0-1-.4-1-1c0-3 2.9-5 6.5-5c1.001 0 1.906.16 2.69.481M5.5 8a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0M16 4.5a3.5 3.5 0 0 1 .906 6.881m-.656 4.869h-1a2.25 2.25 0 0 0 0 4.5h1m2.5-4.5h1a2.25 2.25 0 0 1 0 4.5h-1M15.5 18.5h4");
}

</style>
