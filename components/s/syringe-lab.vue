<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdd5u-vzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:syringe-lab" /></template>
<style>
.pdd5u-vzs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.166 13.591l4.597-4.596a1.75 1.75 0 0 1 2.474 0l1.768 1.768a1.75 1.75 0 0 1 0 2.474l-4.596 4.597a1.75 1.75 0 0 1-2.475 0l-1.768-1.768a1.75 1.75 0 0 1 0-2.475m7.955-3.712l5.657-5.657M4.575 19.425L7.05 16.95m-4.242.707l3.535 3.535m3.182-10.96l4.243 4.243");
}

</style>
