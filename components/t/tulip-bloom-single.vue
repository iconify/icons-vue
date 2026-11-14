<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7rwhccfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tulip-bloom-single" /></template>
<style>
.g7rwhccfh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7 4l2.5 2.5l2.5-3l2.5 3L17 4v5A5 5 0 0 1 7 9Zm5 10v7.5m0-.5q-6-.5-6-6q5 1 6 6Zm0 0q6-.5 6-6q-5 1-6 6Z");
}

</style>
