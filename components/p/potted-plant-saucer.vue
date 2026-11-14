<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvs0_ebbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:potted-plant-saucer" /></template>
<style>
.bvs0_ebbc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 13h13L17 18.75H7ZM4 18.75h16l-1.5 2.75h-13ZM12 13V8m0 1.5c-4.5 0-7-2.5-7-7c4.5 0 7 2.5 7 7ZM12 8c4 0 7-2.25 7-5.5c-4 0-7 2-7 5.5Z");
}

</style>
