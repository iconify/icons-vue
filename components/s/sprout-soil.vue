<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3fs_1epd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sprout-soil" /></template>
<style>
.j3fs_1epd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 19c3.5-4.5 15.5-4.5 19 0Zm9.5-3.25V9m0 2.5C12 8 14.5 5 18 5c0 3.5-2.5 6.5-6 6.5Z");
}

</style>
