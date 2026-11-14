<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gj0d1_gli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:toes" /></template>
<style>
.gj0d1_gli {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 11c0-2.5 3-3.5 6-3.5c3.5 0 6 1.5 6 4s-1.75 3.75-2.5 6c-.75 2.5-1.75 4-3.75 4c-2.25 0-3.5-1.75-3.5-4C8.25 15 6 13.75 6 11Zm-.25-7a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm5.5-1h.01m2.74.25h.01m2.49 1h.01M18.5 6h.01");
}

</style>
