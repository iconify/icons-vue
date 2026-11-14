<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-76_-fkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:olympus-mons" /></template>
<style>
.m-76_-fkb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 16.5c3-1 4.5-7.5 6-9L10.75 9h2.5l1.25-1.5c1.5 1.5 3 8 6 9M2 16.5h20");
}

</style>
