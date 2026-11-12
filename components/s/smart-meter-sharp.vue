<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dk_zsi3cw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:smart-meter-sharp" /></template>
<style>
.dk_zsi3cw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 4h18v17H3Zm5-1v1m8-1v1M6 7h12v5H6Zm4 0v5m4-5v5m-5 4c1-1.333 5-1.333 6 0m-3 2h.01");
}

</style>
