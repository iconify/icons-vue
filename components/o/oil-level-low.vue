<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ruff2q3tm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:oil-level-low" /></template>
<style>
.ruff2q3tm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 7.5h5.75L20.5 5l-5 7.25c-.25.5-.75.75-1.25.75H8a1 1 0 0 1-1-1Zm0 1H4.5a1 1 0 0 0-1 1v.5c0 .5.25.75.75 1L7 12m3-4.5v-2m-1.5 0h3m-8 13q2.25-1.5 4.5 0t4.5 0t4.5 0c1.5 1 2.75 1 3.5.5");
}

</style>
