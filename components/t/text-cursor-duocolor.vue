<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ph92khj4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-cursor-duocolor" /></template>
<style>
.ph92khj4u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 3h2a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H8m8-18h-2a2 2 0 0 0-2 2v14a2 2 0 0 0 2 2h2");
}

</style>
