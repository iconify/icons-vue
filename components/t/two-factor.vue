<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_3fgzl0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:two-factor" /></template>
<style>
.o_3fgzl0x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14 20H3V9.5h13v2m-10-2V7a3.5 3.5 0 0 1 7 0v2.5m-3.5 5.25h.01m6.99 1a2.25 2.25 0 0 1 4.5 0c0 2-4.5 3.25-4.5 5.75h4.75");
}

</style>
