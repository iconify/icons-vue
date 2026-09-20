<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lwmow_bne"/><path class="uogqi4bmc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:water-quality-outline-bold" /></template>
<style>
.lwmow_bne {
  d: path("m12 4 8 8a8 8 0 0 1 -16 0Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uogqi4bmc {
  d: path("m8 13 3 3 5 -5");
}

</style>
