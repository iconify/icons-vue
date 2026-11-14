<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxsbj2xee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pest-neem-oil" /></template>
<style>
.kxsbj2xee {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 10.5H14V21H4.5Zm2 0V4h7L16 6v1.5h-4.5v3M19 3.75h.01m-.01 3h.01m-.01 3h.01");
}

</style>
