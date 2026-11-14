<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpkqw4azz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:taka-sign" /></template>
<style>
.cpkqw4azz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 5.5c0-1.1.9-2 2-2s2 .9 2 2V15c0 3 2.25 5.25 5 5.25s5-2.25 5-5c0-1.75-1-3-2.5-3.5M5 9.5h9.5");
}

</style>
