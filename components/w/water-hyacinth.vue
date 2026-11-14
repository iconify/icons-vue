<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="caz7z9bbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:water-hyacinth" /></template>
<style>
.caz7z9bbr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 7a3 4.5 0 1 0 6 0a3 4.5 0 1 0-6 0Zm3 4.5V17m0 0c-3.5 0-6.5-2-6.5-5C9 12 12 14 12 17Zm0 0c3.5 0 6.5-2 6.5-5c-3.5 0-6.5 2-6.5 5Zm-9 3.5q2.25-.75 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
