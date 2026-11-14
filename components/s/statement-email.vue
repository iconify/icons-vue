<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o341uablf"/><path class="e1f_o0bas"/><path class="d8088zs0w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:statement-email" /></template>
<style>
.d8088zs0w {
  d: path("m15.5 16.5l2.5 2l2.5-2");
}

.e1f_o0bas {
  d: path("M14.75 15.25h6.5v5.5h-6.5Z");
}

.o341uablf {
  d: path("M11.9 21.5H4.5v-19h15v9.9M8 7h8m-8 3.5h8M8 14h3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
