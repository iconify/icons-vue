<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avwn_5ruv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:review-diff-stats" /></template>
<style>
.avwn_5ruv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 4.5v7M2.75 8h7m-7 9h7m3.5-11.25h8v4.5h-8Zm0 9h4.5v4.5h-4.5Z");
}

</style>
