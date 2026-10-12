<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5fg9ybzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:swim-trunks-sharp" /></template>
<style>
.t5fg9ybzc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 3.25h15.5v3H4.25zm1.5 5.25H19.5l.21 1.23l1.33 8.04l.21 1.23l-1.23.21l-5.04.83l-1.23.21l-.36-1.2l-1.03-3.35l-.36-1.2l-.36 1.2l-1.03 3.35l-.36 1.2l-1.23-.21l-5.04-.83L2.75 19l.21-1.23l1.33-8.04l.21-1.23zm5-2.25l-.75 4.5m3.25-4.5l.75 4.5");
}

</style>
