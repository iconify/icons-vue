<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgfxckblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zodiac-capricorn-duotone-round" /></template>
<style>
.qgfxckblq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 3a4 4 0 0 1 4 4v9m0-9a3 3 0 0 1 6 0v11a3 3 0 0 1-3 3m3-6a3 3 0 0 0 6 0m0 0a3 3 0 0 0-6 0");
}

</style>
