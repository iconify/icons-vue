<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t2bw0sbjo"/><circle class="oof2upb3i"/><path class="wm9mbw5pt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:prosthetic-leg" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oof2upb3i {
  cx: 12px;
  cy: 13px;
  r: 1.5px;
}

.t2bw0sbjo {
  d: path("M9.75 2.75h4.5q.75 0 .57.73l-1.14 4.79q-.18.73-.93.73h-1.5q-.75 0-.93-.73L9.18 3.48q-.18-.73.57-.73");
}

.wm9mbw5pt {
  d: path("M12 14.5v3.75M9 20.5V19q0-.75.75-.75H12q.75 0 1.47.21l3.81 1.08q.72.21.72.96t-.75.75h-7.5q-.75 0-.75-.75");
}

</style>
