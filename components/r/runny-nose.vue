<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6hzz_-ot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:runny-nose" /></template>
<style>
.h6hzz_-ot {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 2.75h4c1.75 3 5.5 6.75 5.5 9.5A2.25 2.25 0 0 1 11 14.5h-1v1.75l1.25 1.25L10 18.75v2.5H3.75Zm4.75 9.5H10m5.75 1.5c.95 1.3 1.75 2.25 1.75 3.1a1.75 1.75 0 0 1-3.5 0c0-.85.8-1.8 1.75-3.1");
}

</style>
