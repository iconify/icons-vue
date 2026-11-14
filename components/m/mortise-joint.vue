<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_ctrs9hi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mortise-joint" /></template>
<style>
.p_ctrs9hi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12h6v5h7v-5h6v8.5h-19ZM10 3h4a1.5 1.5 0 0 1 1.5 1.5v3A1.5 1.5 0 0 1 14 9h-4a1.5 1.5 0 0 1-1.5-1.5v-3A1.5 1.5 0 0 1 10 3");
}

</style>
