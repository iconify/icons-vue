<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrp3b5b0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:take-ferry" /></template>
<style>
.hrp3b5b0u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11.5h19l-3 5h-13Zm3.5 0v-4a1 1 0 0 1 1-1h8l3 5M8.5 3h3v3.5h-3Zm-5 18q2.75-1.5 5.5 0t5.5 0t5.5 0");
}

</style>
