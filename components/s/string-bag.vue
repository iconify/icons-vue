<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wagl_sloo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:string-bag" /></template>
<style>
.wagl_sloo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 9h17l-1.75 10c-.25 1.5-1.75 2.5-3.25 2.5h-7c-1.5 0-3-1-3.25-2.5ZM7 9c0-5.5 3.5-5.5 3.5 0m3 0c0-5.5 3.5-5.5 3.5 0M4.25 13.25L8.5 9m-3 10.5L16 9m-4 12.5l7.75-8m0-.25L15.5 9m3 10.5L8 9m4 12.5l-7.75-8");
}

</style>
