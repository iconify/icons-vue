<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6i1uq8sy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:senate-chamber-sharp" /></template>
<style>
.g6i1uq8sy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 16.25a9 9 0 0 1 1.24-4.55m.61-.92A9 9 0 0 1 8.6 7.92m1.04-.36a9 9 0 0 1 4.72 0m1.04.36a9 9 0 0 1 3.75 2.86m.61.92A9 9 0 0 1 21 16.25m-14.5 0a5.5 5.5 0 0 1 2.22-4.41m.81-.5a5.5 5.5 0 0 1 4.94 0m.81.5a5.5 5.5 0 0 1 2.22 4.41m-7.5 0h4v5h-4z");
}

</style>
