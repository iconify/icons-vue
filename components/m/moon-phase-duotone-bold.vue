<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="q4vnxcbew"/><path class="tfz8tiblq"/><path class="w88m64x8i"/><path class="hba66yqou"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:moon-phase-duotone-bold" /></template>
<style>
.hba66yqou {
  d: path("M18 7a5 5 0 1 0 0 10 4 4 0 0 1 0 -10");
}

.q4vnxcbew {
  fill: currentColor;
  d: path("M2 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tfz8tiblq {
  fill: currentColor;
  d: path("M18 7a5 5 0 1 0 0 10 4 4 0 0 1 0 -10");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.w88m64x8i {
  d: path("M2 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

</style>
