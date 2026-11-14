<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krsb5pbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:scout-sports" /></template>
<style>
.krsb5pbdd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 6h6.5v8.5H4Zm9.5 0H20v8.5h-6.5Zm-3 3h3M7.25 6c0-2.5 2.25-3.5 4.75-3.5s4.75 1 4.75 3.5M3 21.5c0-2.5 3.5-4.25 9-4.25s9 1.75 9 4.25");
}

</style>
