<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n87boac3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:repost-count" /></template>
<style>
.n87boac3y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 6.75A7.5 7.5 0 0 1 19.5 12m-1.75-1.75L19.5 12l1.75-1.75m-4 7A7.5 7.5 0 0 1 4.5 12m-1.75 1.75L4.5 12l1.75 1.75m2.75-4v4.5m3-4.5v4.5m3-4.5v4.5");
}

</style>
