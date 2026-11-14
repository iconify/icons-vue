<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2bx6hb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:potted-flower" /></template>
<style>
.s2bx6hb5d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 14.5h13l-1.75 7h-9.5ZM8.5 3l1.75 2L12 2.5L13.75 5l1.75-2v2.5a3.5 3.5 0 0 1-7 0ZM12 9v5.5m0 0q0-3.5 4.5-4");
}

</style>
