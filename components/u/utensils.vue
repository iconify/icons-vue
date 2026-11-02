<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rp4b-_bwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:utensils" /></template>
<style>
.rp4b-_bwt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 14V3a5 5 0 0 0-5 5v4a2 2 0 0 0 2 2zm0 0v7M3 3v6a2 2 0 0 0 2 2h4a2 2 0 0 0 2-2V3M7 3v18");
}

</style>
