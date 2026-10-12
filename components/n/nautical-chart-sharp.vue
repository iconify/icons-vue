<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="l7yfq-b6e"/><path class="bri22rb1x"/><path class="zf_bozu1g"/><path class="iecxesbqy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:nautical-chart-sharp" /></template>
<style>
.bri22rb1x {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 9.25c2.5 0 3.5 2 6 2s3-3.75 5.5-3.75c1.5 0 2 1 3.25 1");
}

.iecxesbqy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6 17.25l11.75-5.75m-3.25-1l3.25 1l-1.25 3");
}

.l7yfq-b6e {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.75h18.5v16.5H2.75z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zf_bozu1g {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.5 17h.01M6.5 13.5h.01");
}

</style>
