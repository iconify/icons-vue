<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxrmq-37u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:parking-lights" /></template>
<style>
.zxrmq-37u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 8c-2.25 0-3.75 1.75-3.75 4s1.5 4 3.75 4Zm3 0c2.25 0 3.75 1.75 3.75 4s-1.5 4-3.75 4Zm-11 .5l1.75.75M2.5 12h1.75M2.5 15.5l1.75-.75M21.5 8.5l-1.75.75M21.5 12h-1.75m1.75 3.5l-1.75-.75");
}

</style>
