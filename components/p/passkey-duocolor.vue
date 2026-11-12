<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bpu8n8bvx"/><path class="ivkz7dbmj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:passkey-duocolor" /></template>
<style>
.bpu8n8bvx {
  stroke-opacity: 0.4;
  d: path("M19 12v-2h-3m3 2v5m0-5h-3m1 7a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

.ivkz7dbmj {
  d: path("M4 7a4 4 0 1 0 8 0a4 4 0 0 0-8 0M3 21c0-3.314 2.239-6 5-6s5 2.686 5 6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
