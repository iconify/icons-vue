<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m_yh748zk"/><path class="um97dsikq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:poll-duocolor-round" /></template>
<style>
.m_yh748zk {
  stroke-opacity: 0.4;
  d: path("M11 7h10M11 17h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.um97dsikq {
  d: path("M3 7a2 2 0 1 0 4 0a2 2 0 0 0-4 0m0 10a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
