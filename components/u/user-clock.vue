<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="rknchmb5r"/><path class="kf_mvwa8r"/><circle class="xrq1-2bey"/><path class="ky4djfb-h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:user-clock" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kf_mvwa8r {
  d: path("M4 20.25h11a.75.75 0 0 0 .75-.75c0-3-2.8-5.25-6.25-5.25S3.25 16.5 3.25 19.5a.75.75 0 0 0 .75.75");
}

.ky4djfb-h {
  d: path("M18 9.5V11l1 .75");
}

.rknchmb5r {
  cx: 9.5px;
  cy: 7.75px;
  r: 3.75px;
}

.xrq1-2bey {
  cx: 18px;
  cy: 11px;
  r: 3.25px;
}

</style>
