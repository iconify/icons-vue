<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfzuqpsjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:store-dry" /></template>
<style>
.nfzuqpsjr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10a9.5 7.5 0 0 1 19 0a3.25 2 0 0 0-6.25 0a3.25 2 0 0 0-6.5 0a3.25 2 0 0 0-6.25 0m7.625 2.75h3.75A1.125 1.125 0 0 1 15 13.875A1.125 1.125 0 0 1 13.875 15h-3.75A1.125 1.125 0 0 1 9 13.875a1.125 1.125 0 0 1 1.125-1.125m.5 2.25h2.75A2.625 2.625 0 0 1 16 17.625v1.25a2.625 2.625 0 0 1-2.625 2.625h-2.75A2.625 2.625 0 0 1 8 18.875v-1.25A2.625 2.625 0 0 1 10.625 15");
}

</style>
