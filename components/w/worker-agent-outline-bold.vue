<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pemn838wn"/><path class="eu2so4bxo"/><path class="vi-y66bgi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:worker-agent-outline-bold" /></template>
<style>
.eu2so4bxo {
  d: path("M7 16a5 5 0 0 1 10 0");
}

.pemn838wn {
  d: path("M9 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vi-y66bgi {
  d: path("M8 20.5A1.5 1.5 0 0 1 9.5 19h5a1.5 1.5 0 0 1 1.5 1.5 1.5 1.5 0 0 1 -1.5 1.5h-5A1.5 1.5 0 0 1 8 20.5");
}

</style>
