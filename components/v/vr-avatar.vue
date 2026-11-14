<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-5jp2rpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:vr-avatar" /></template>
<style>
.l-5jp2rpv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 6.5h11a2 2 0 0 1 2 2v1a2 2 0 0 1-2 2H14L13 10h-2l-1 1.5H6.5a2 2 0 0 1-2-2v-1a2 2 0 0 1 2-2Zm-.25 0a6 6 0 0 1 11.5 0m-11 5a6 6 0 0 0 10.5 0M4 21.5c0-2.75 3.5-4.25 8-4.25s8 1.5 8 4.25");
}

</style>
