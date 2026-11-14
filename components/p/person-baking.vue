<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0kjwc7cq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:person-baking" /></template>
<style>
.j0kjwc7cq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 11V8.25A2.75 2.75 0 1 1 12 4a2.75 2.75 0 1 1 3.5 4.25V11Zm.25 0v1a3.25 3.25 0 0 0 6.5 0v-1M4 21.5c0-2.5 3.25-3.75 8-3.75q.907 0 1.737.061m3.083.534l1.639-1.147a1.5 1.5 0 0 1 2.089.368a1.5 1.5 0 0 1-.368 2.089l-1.639 1.147a1.5 1.5 0 0 1-2.089-.368a1.5 1.5 0 0 1 .368-2.089M15 21.5l1.25-1m4.5-3l1.25-1");
}

</style>
