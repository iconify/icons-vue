<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="biku14z-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:socks" /></template>
<style>
.biku14z-s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 2.75h6.5V12l4.65 4.3a2.75 2.75 0 0 1-1.87 4.95H11.5a3.5 3.5 0 0 1-3.5-3.5Zm0 3.5h6.5m2 11l-1.75 2.5");
}

</style>
