<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-gku3bvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:star-schema" /></template>
<style>
.j-gku3bvk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 9.5h5v5h-5Zm1-7.25h3v3h-3ZM18.25 8h3v3h-3Zm-3 9.25h3v3h-3Zm-9.5 0h3v3h-3ZM2.75 8h3v3h-3ZM12 9.5V6.25M14.5 11l2.75-.75M14 14.5l1.5 2.25M10 14.5l-1.5 2.25m1-5.75l-2.75-.75");
}

</style>
