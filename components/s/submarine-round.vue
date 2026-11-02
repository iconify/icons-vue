<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9a1m00rw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:submarine-round" /></template>
<style>
.p9a1m00rw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 20h-7a3 3 0 0 1-3-3v-2a3 3 0 0 1 3-3V9a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v3h3a4 4 0 1 1 0 8M3 12v8m0-4h4m5-8V6a2 2 0 0 1 2-2h2m-4 12h.01M16 16h.01");
}

</style>
