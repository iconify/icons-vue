<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnwuh_txb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wig-stand" /></template>
<style>
.xnwuh_txb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.5 2.5C10.25 2.5 8 4.75 8 8l-1.5 2.5L8 11v1.5c0 1 .75 1.75 1.75 1.75H12m.5 0v4.25M7 19.75a5.5 1.5 0 1 0 11 0a5.5 1.5 0 1 0-11 0M13.5 2.5c3.5 0 6 2.5 6 6c0 2.5-1 4 0 6s0 2.5.5 3.5M14.5 6c1.5 2 1 4.5 1.75 6.5s0 3 .5 4.5");
}

</style>
