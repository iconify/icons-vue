<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbzbvvieb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:winter-solstice" /></template>
<style>
.wbzbvvieb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 17.5a7 7 0 0 1 14 0m-16.5 0h19M12 7.5v-3m7 6l1.75-1.75M5 10.5L3.25 8.75");
}

</style>
