<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdo5-bbjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:poll" /></template>
<style>
.vdo5-bbjb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 7a2 2 0 1 0 4 0a2 2 0 0 0-4 0m0 10a2 2 0 1 0 4 0a2 2 0 0 0-4 0m8-10h10M11 17h6");
}

</style>
