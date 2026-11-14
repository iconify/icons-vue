<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9ts37n8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:repotting-pot-size" /></template>
<style>
.y9ts37n8y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 4h8.5A1.5 1.5 0 0 1 14 5.5A1.5 1.5 0 0 1 12.5 7H4a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 4 4m-.5 3L5 19.5h6.5L13 7m4.375 5h2.75a1.375 1.375 0 0 1 1.375 1.375a1.375 1.375 0 0 1-1.375 1.375h-2.75A1.375 1.375 0 0 1 16 13.375A1.375 1.375 0 0 1 17.375 12m-.875 2.75l.75 4.75h3l.75-4.75");
}

</style>
