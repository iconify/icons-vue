<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="clz013bew"/><path class="eawry1bwu"/><path class="ww6qi_bzz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:triage-agent-duotone-bold" /></template>
<style>
.clz013bew {
  fill: currentColor;
  d: path("M10 11h11l-4 4v5h-3v-5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.eawry1bwu {
  d: path("M8 3.33a3.5 3.5 0 1 1 -2.96 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ww6qi_bzz {
  d: path("M10 11h11l-4 4v5h-3v-5Z");
}

</style>
