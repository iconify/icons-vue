<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ll3yz4qep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-festival" /></template>
<style>
.ll3yz4qep {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 21L7.5 9l7.5 7.5Zm8-18l.75 3.5M15 9l4-4m-1.5 7.25l3.5-.75M18 3h.01M21 7.5h.01");
}

</style>
