<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmnyw6bnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:promo-bogo" /></template>
<style>
.cmnyw6bnt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.625 8.75h1a2.625 2.625 0 0 1 2.625 2.625v1A2.625 2.625 0 0 1 5.625 15h-1A2.625 2.625 0 0 1 2 12.375v-1A2.625 2.625 0 0 1 4.625 8.75m13.75 0h1A2.625 2.625 0 0 1 22 11.375v1A2.625 2.625 0 0 1 19.375 15h-1a2.625 2.625 0 0 1-2.625-2.625v-1a2.625 2.625 0 0 1 2.625-2.625m-6.375 2v2.5M10.75 12h2.5");
}

</style>
