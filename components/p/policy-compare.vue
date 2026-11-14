<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpo-z8b5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:policy-compare" /></template>
<style>
.zpo-z8b5z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 5h-2.5V2.5h-2.5A1.75 1.75 0 0 0 2.5 4.25v15.5a1.75 1.75 0 0 0 1.75 1.75H7.5a1.75 1.75 0 0 0 1.75-1.75zl-2.5-2.5M21.5 5H19V2.5h-2.5a1.75 1.75 0 0 0-1.75 1.75v15.5a1.75 1.75 0 0 0 1.75 1.75h3.25a1.75 1.75 0 0 0 1.75-1.75zL19 2.5M12 5v14");
}

</style>
