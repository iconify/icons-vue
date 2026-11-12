<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="we40hv38q"/><path class="vkba6k5jk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:parentheses-linear" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vkba6k5jk {
  d: path("M15 22C18 20.268 21 16.6925 21 12C21 7.30754 18 3.73205 15 2");
}

.we40hv38q {
  d: path("M9 22C6 20.268 3 16.6925 3 12C3 7.30754 6 3.73205 9 2");
}

</style>
