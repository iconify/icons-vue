<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngfz21zxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tote-bag-reusable" /></template>
<style>
.ngfz21zxj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.625 10h10.75A2.625 2.625 0 0 1 20 12.625v6.25a2.625 2.625 0 0 1-2.625 2.625H6.625A2.625 2.625 0 0 1 4 18.875v-6.25A2.625 2.625 0 0 1 6.625 10M6.5 10V8a4 4 0 0 1 8 0v2m3 0V6.5m0 0c0-2.5 1.5-4 4-4c0 2.5-1.5 4-4 4");
}

</style>
