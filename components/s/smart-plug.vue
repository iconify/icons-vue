<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ewfr0xbyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:smart-plug" /></template>
<style>
.ewfr0xbyy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11h9v3a4.5 4.5 0 0 1-9 0Zm2.5 0V7m4 4V7m-2 11.5v3m5.368-15.424a5 5 0 0 1 4.056 4.056m-3.361-7.995a9 9 0 0 1 7.3 7.3");
}

</style>
