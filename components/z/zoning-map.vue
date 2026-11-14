<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l7mb4vb_t"/><path class="heynorb3c"/><path class="rxunn00kg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:zoning-map" /></template>
<style>
.heynorb3c {
  fill: currentColor;
  d: path("M3.526 4.158L8.06 2.647a1.5 1.5 0 0 1 .886-.02l1.966.562A1.5 1.5 0 0 1 12 4.631V10.5a1.5 1.5 0 0 1-1.5 1.5H4a1.5 1.5 0 0 1-1.5-1.5V5.581a1.5 1.5 0 0 1 1.026-1.423");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l7mb4vb_t {
  d: path("M3.526 4.158L8.06 2.647a1.5 1.5 0 0 1 .886-.02l6.108 1.746a1.5 1.5 0 0 0 .886-.02l3.586-1.195A1.5 1.5 0 0 1 21.5 4.581v13.838a1.5 1.5 0 0 1-1.026 1.423l-4.534 1.511a1.5 1.5 0 0 1-.886.02l-6.108-1.746a1.5 1.5 0 0 0-.886.02l-3.586 1.195A1.5 1.5 0 0 1 2.5 19.419V5.581a1.5 1.5 0 0 1 1.026-1.423M12 3.5v17M2.5 12h19");
}

.rxunn00kg {
  d: path("m5 19l2-2M17 7l2-2");
}

</style>
