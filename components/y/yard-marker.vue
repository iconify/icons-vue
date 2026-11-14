<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sx31f_bag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:yard-marker" /></template>
<style>
.sx31f_bag {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.5 6l2.25-2v16m2.75-8a4.5 8 0 1 0 9 0a4.5 8 0 1 0-9 0m-7.75-1za.769.769 0 0 1 1.25.601v.798A.769.769 0 0 1 3.75 13a1.28 1.28 0 0 1 0-2");
}

</style>
