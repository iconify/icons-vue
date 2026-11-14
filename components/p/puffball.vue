<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sx1zuwb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:puffball" /></template>
<style>
.sx1zuwb_d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 6.75C6 7.25 3.5 9.75 3.5 13c0 3 2.25 4.75 5 5.25L8 21.5h8l-.5-3.25c2.75-.5 5-2.25 5-5.25c0-3.25-2.5-5.75-6.75-6.25M8.5 18.25h7M12 3.5h.01m2.74-.75h.01");
}

</style>
