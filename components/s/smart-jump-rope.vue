<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4t0iabis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:smart-jump-rope" /></template>
<style>
.l4t0iabis {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.5h3.5V10H3Zm8 0h3.5V10H11ZM4.75 10c0 11.5 8 11.5 8 0m3.75 6.5l4.25 3L18.5 21v-6.5l2.25 1.5l-4.25 3");
}

</style>
