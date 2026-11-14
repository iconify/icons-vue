<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcxcsgbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sludge" /></template>
<style>
.vcxcsgbrm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5c0-6.5 3.5-10 7.5-10c3 0 4 2.5 5.5 2.5c3.5 0 6 2.5 6 7.5Zm13.25-12a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM11.25 5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

</style>
