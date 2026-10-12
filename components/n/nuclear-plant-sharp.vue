<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uz-tk2b2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:nuclear-plant-sharp" /></template>
<style>
.uz-tk2b2r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 21.25C4.5 17 5 13 4.25 8h6c-.75 5-.25 9 1.5 13.25Zm2-16a1.75 1.75 0 0 1 3-1.25a1.75 1.75 0 0 1 3.25.75m4.25 16.5v-3.5a3 3 0 0 1 6 0v3.5Z");
}

</style>
