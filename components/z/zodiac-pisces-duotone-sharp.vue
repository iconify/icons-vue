<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyr-ws_tx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zodiac-pisces-duotone-sharp" /></template>
<style>
.dyr-ws_tx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 3a15 15 0 0 1 0 18M20 3a15 15 0 0 0 0 18M5 12h2m0 0h10m0 0h2");
}

</style>
