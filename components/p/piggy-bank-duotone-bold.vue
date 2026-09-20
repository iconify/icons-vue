<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="kb7le7zyg"/><path class="p88ypbxwz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:piggy-bank-duotone-bold" /></template>
<style>
.kb7le7zyg {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 12.5a7 7 0 1 1 14 0 7 7 0 1 1 -14 0m12 -2h5v4h-5M7.5 19v3m7 -3v3m-5 -19v2.5m6 2.5 2 -2 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.p88ypbxwz {
  d: path("M4 12.5a7 7 0 1 1 14 0 7 7 0 1 1 -14 0m12 -2h5v4h-5M7.5 19v3m7 -3v3m-5 -19v2.5m6 2.5 2 -2 2 2");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
