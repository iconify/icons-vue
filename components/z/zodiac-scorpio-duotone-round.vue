<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1pt29g_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zodiac-scorpio-duotone-round" /></template>
<style>
.w1pt29g_i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3a2 2 0 0 1 2 2v10M5 5a2 2 0 1 1 4 0v10M9 5a2 2 0 1 1 4 0v10a3 3 0 0 0 3 3m0 0h5m-3-3l3 3l-3 3");
}

</style>
