<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dw4k6db3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-parking-sharp" /></template>
<style>
.dw4k6db3s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 5V3h6l2 5l-3 3l5 5l3-3l5 2v6h-2C10.163 21 3 13.837 3 5m13-2v6m0-6h2a2 2 0 1 1 0 4h-2");
}

</style>
