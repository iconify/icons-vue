<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8es2_b0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:plant-alert" /></template>
<style>
.p8es2_b0g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 13.5h9l-1 7h-7Zm4.5 0v-5c-.25-3-2.25-5-5.25-5c0 3 2.25 5 5.25 5C8.25 5.25 10.25 3 13.25 3c0 3-2 5.5-5.25 5.5m10 6.25v3.5M18 21h.01");
}

</style>
