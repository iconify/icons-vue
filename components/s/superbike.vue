<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ie_a0y6ql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:superbike" /></template>
<style>
.ie_a0y6ql {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 16a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm12 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM3 9.5h6l2.5 2.5H14l2-6h2.5l2 3.5M18 16l-2.5-8.5M6 16l5.5-4");
}

</style>
