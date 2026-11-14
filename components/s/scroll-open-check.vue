<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9wnhcbay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:scroll-open-check" /></template>
<style>
.d9wnhcbay {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h15v4h-15Zm11.8 19H2.5v-4h8.8M5 6.5v11m10-11v7.8M8 12h4m2.75 6l2 2L21 15.75");
}

</style>
