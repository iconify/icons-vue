<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ajw0nrbny"/><path class="a2oa0jy6d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paper-plane-duotone-round" /></template>
<style>
.a2oa0jy6d {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6L6 8c-1.107.369-.476 2.262 1 3l2 1a6.7 6.7 0 0 1 3 3l1 2c.738 1.476 2.631 2.107 3 1l4-12c.412-1.236-.764-2.412-2-2zm-1 7l3-3");
}

.ajw0nrbny {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17.684 3.051a2.582 2.582 0 0 1 3.265 3.265l-4 12c-.187.56-.612.986-1.178 1.159c-.476.145-.981.098-1.449-.058a3.7 3.7 0 0 1-1.25-.728a4 4 0 0 1-.966-1.242l-1-2a5.72 5.72 0 0 0-2.553-2.553l-2-1a4 4 0 0 1-1.242-.966a3.7 3.7 0 0 1-.728-1.25c-.156-.468-.203-.973-.058-1.449a1.78 1.78 0 0 1 1.159-1.178Z");
}

.ft5dv1b6b {
  fill: none;
}

</style>
