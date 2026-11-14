<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5po068ne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tornado-shelter" /></template>
<style>
.s5po068ne {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.079 13.479l3.25-2.925a1.75 1.75 0 0 1 2.342 0l3.25 2.925a1.75 1.75 0 0 1 .579 1.3v4.471A1.75 1.75 0 0 1 10.75 21h-6.5a1.75 1.75 0 0 1-1.75-1.75v-4.471a1.75 1.75 0 0 1 .579-1.3M13 3.5h8.5m-7 4H21m-5 4h4m-3 4h2.5");
}

</style>
