<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpr8f4bnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:throw-in" /></template>
<style>
.mpr8f4bnv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 5.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm1 6.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM9 5.5L5 9.75l2.5 6.75v5m7.5-16l4 4.25l-2.5 6.75v5");
}

</style>
