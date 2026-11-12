<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9lvkwenq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:network-off-round" /></template>
<style>
.f9lvkwenq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3h1a2 2 0 0 1 2 2v1M3 18a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v1a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2zm18 0v1a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2v-1a2 2 0 0 1 2-2h2M6 16a4 4 0 0 1 4-4h4a4 4 0 0 1 1.176.176M5 2l17 17");
}

</style>
