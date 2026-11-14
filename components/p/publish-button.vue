<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ko88usznn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:publish-button" /></template>
<style>
.ko88usznn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.364 4.699L6.339 8.914a1.5 1.5 0 0 0-.25 2.679l3.607 2.22a1.5 1.5 0 0 1 .491.491l2.22 3.607a1.5 1.5 0 0 0 2.679-.25l4.215-11.025a1.5 1.5 0 0 0-1.937-1.937M10 14L20.5 3.5");
}

</style>
