<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1akn2vld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-pi-sharp" /></template>
<style>
.x1akn2vld {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3L21 3L21 21L3 21L3 3ZM6.5 8.5L17.5 8.5M10 8.5L10 16M14 8.5L14 14C14 14.8285 14.6716 15.5 15.5 15.5L16 15.5");
}

</style>
