<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="g2orrxpuo"/><path class="t_ap1vbux"/><circle class="trxuqqs3g"/><path class="zajpd0huc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:user-target" /></template>
<style>
.g2orrxpuo {
  cx: 9.5px;
  cy: 7.75px;
  r: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t_ap1vbux {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 20.25h11a.75.75 0 0 0 .75-.75c0-3-2.8-5.25-6.25-5.25S3.25 16.5 3.25 19.5a.75.75 0 0 0 .75.75");
}

.trxuqqs3g {
  cx: 18px;
  cy: 12px;
  r: 3.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zajpd0huc {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 12h.01");
}

</style>
