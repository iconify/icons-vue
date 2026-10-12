<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="fzvmmb14m"/><path class="lwhx5sb4u"/><path class="w4_qq7onx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pizza-cutter" /></template>
<style>
.fzvmmb14m {
  cx: 8.75px;
  cy: 15.25px;
  r: 6px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lwhx5sb4u {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 15.25h.01");
}

.w4_qq7onx {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.99 11.01l2.12-2.12m.36.36l-.72-.72q-.88-.88 0-1.76l3.13-3.13q.88-.88 1.76 0l.72.72q.88.88 0 1.76l-3.13 3.13q-.88.88-1.76 0");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
