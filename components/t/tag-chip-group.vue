<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6cf0g8ts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tag-chip-group" /></template>
<style>
.n6cf0g8ts {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 4.5h9a3 3 0 0 1 3 3a3 3 0 0 1-3 3h-9a3 3 0 0 1-3-3a3 3 0 0 1 3-3m0 9H8a3 3 0 0 1 3 3a3 3 0 0 1-3 3H5.5a3 3 0 0 1-3-3a3 3 0 0 1 3-3m11.25 0h1.75a3 3 0 0 1 3 3a3 3 0 0 1-3 3h-1.75a3 3 0 0 1-3-3a3 3 0 0 1 3-3M5.5 7.5h.01m-.01 9h.01m11.24 0h.01");
}

</style>
