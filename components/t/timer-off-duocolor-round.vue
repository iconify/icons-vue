<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lmxlbqbeq"/><path class="uxa981qcs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:timer-off-duocolor-round" /></template>
<style>
.lmxlbqbeq {
  stroke-opacity: 0.4;
  d: path("m3 2l19 19");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uxa981qcs {
  d: path("M7.432 6.432a8 8 0 1 0 11.137 11.137M20 13a8 8 0 0 0-8-8m-2-2h4m-2 0v2m6 2l2-2");
}

</style>
