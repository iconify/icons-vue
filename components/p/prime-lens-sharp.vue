<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ki3rflbuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:prime-lens-sharp" /></template>
<style>
.ki3rflbuh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 7.5h-2.5v9h2.5Zm0-3.75h6v16.5h-6zm3 0v16.5M17.25 7q2.5 5 0 10");
}

</style>
