<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygzll7x7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:plant-sharp" /></template>
<style>
.ygzll7x7m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 13.25h12.5l-1.4 6.6l-.283 1.388l-1.417.012h-6.3l-1.417-.012l-.283-1.388Zm6.25 0v-4.5m-.75 1.5q-5.625 0-6-5.25q5.625 0 6 5.25Zm1.5-1.5c.25-3.5 2.25-5.5 6-5.5c-.25 3.5-2.25 5.5-6 5.5Z");
}

</style>
