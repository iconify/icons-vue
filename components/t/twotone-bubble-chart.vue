<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="inkt5twsv"/><circle class="x5pyf_b-v"/><circle class="g7mb5_blv"/><path class="m5ux1vdct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-bubble-chart" /></template>
<style>
.g7mb5_blv {
  cx: 7px;
  cy: 14px;
  r: 2px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-3, 0.3);
}

.inkt5twsv {
  fill: currentColor;
  d: path("M16.5 12c1.93 0 3.5-1.57 3.5-3.5S18.43 5 16.5 5S13 6.57 13 8.5s1.57 3.5 3.5 3.5");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.m5ux1vdct {
  fill: currentColor;
  d: path("M7 18c2.21 0 4-1.79 4-4s-1.79-4-4-4s-4 1.79-4 4s1.79 4 4 4m0-6c1.1 0 2 .9 2 2s-.9 2-2 2s-2-.9-2-2s.9-2 2-2m11.01 6c0-1.65-1.35-3-3-3s-3 1.35-3 3s1.35 3 3 3s3-1.35 3-3m-4 0c0-.55.45-1 1-1s1 .45 1 1s-.45 1-1 1s-1-.45-1-1m2.49-4c3.03 0 5.5-2.47 5.5-5.5S19.53 3 16.5 3S11 5.47 11 8.5s2.47 5.5 5.5 5.5m0-9C18.43 5 20 6.57 20 8.5S18.43 12 16.5 12S13 10.43 13 8.5S14.57 5 16.5 5");
}

.x5pyf_b-v {
  cx: 15.01px;
  cy: 18px;
  r: 1px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
