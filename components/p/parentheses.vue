<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r0p_q6brq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:parentheses" /></template>
<style>
.r0p_q6brq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 3.5c-2.75 2.25-4 5.25-4 8.5s1.25 6.25 4 8.5m7-17c2.75 2.25 4 5.25 4 8.5s-1.25 6.25-4 8.5");
}

</style>
