<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8qrxwbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:umpire" /></template>
<style>
.h8qrxwbmd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M20.5 8h-13a4.5 4.5 0 0 1 9 0M8 8v1.5a4 4 0 0 0 8 0V8M4.5 21.5C4.5 19 7.75 17 12 17s7.5 2 7.5 4.5");
}

</style>
