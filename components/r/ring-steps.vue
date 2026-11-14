<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9rhq5vjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ring-steps" /></template>
<style>
.d9rhq5vjt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 2.5H8v19H4.5ZM8 6q6.5 1.75 13 0M8 10.5q6.5 1.75 13 0M8 15q6.5 1.75 13 0M3 21.5h18");
}

</style>
