<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jgimyxb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:smart-lock" /></template>
<style>
.jgimyxb6e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.5 19.4V21h-10V10h10v5.1M4.75 10V6.75a2.75 2.75 0 0 1 5.5 0V10M7.5 13.5v4m6.75-.25a5.3 5.3 0 0 1 7.5 0M16 19a2.83 2.83 0 0 1 4 0m-2 2h.01");
}

</style>
