<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmf3ixk6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rubber-plant" /></template>
<style>
.nmf3ixk6o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 17h8l-1 4.5H9Zm4 0V9m0 0c-3-2-2.5-5 0-6.5C14.5 4 15 7 12 9m0 4.5c-3 2-7.5 0-8.5-4c3.5-1 7 .5 8.5 4m0-1.5c3 2 7.5 0 8.5-4c-3.5-.75-7 .75-8.5 4");
}

</style>
