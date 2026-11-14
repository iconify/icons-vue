<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_6p00b7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:toothbrush-kit" /></template>
<style>
.w_6p00b7g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 21V8.5M7.5 3zA1.5 1.5 0 0 1 9 4.5V7a1.5 1.5 0 0 1-1.5 1.5A1.5 1.5 0 0 1 6 7V4.5A1.5 1.5 0 0 1 7.5 3m6.505 3h3.99a1.75 1.75 0 0 1 1.734 1.986l-1.023 7.5A1.75 1.75 0 0 1 16.972 17h-1.944a1.75 1.75 0 0 1-1.734-1.514l-1.023-7.5A1.75 1.75 0 0 1 14.005 6M15.5 17h1a1.5 1.5 0 0 1 1.5 1.5v1a1.5 1.5 0 0 1-1.5 1.5h-1a1.5 1.5 0 0 1-1.5-1.5v-1a1.5 1.5 0 0 1 1.5-1.5M12 3h8");
}

</style>
