<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aaobfcbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-call" /></template>
<style>
.aaobfcbzq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 5a2 2 0 0 1 2-2h3c.995 0 1.8.403 2 1l1 3c.153.46-.234 1.234-1 2l-1 1a1.414 1.414 0 0 0 0 2l3 3a1.414 1.414 0 0 0 2 0l1-1c.766-.766 1.54-1.153 2-1l3 1c.597.2 1 1.005 1 2v3a2 2 0 0 1-2 2C10.163 21 3 13.837 3 5m12 1a3 3 0 0 1 3 3m-3-6a6 6 0 0 1 6 6");
}

</style>
