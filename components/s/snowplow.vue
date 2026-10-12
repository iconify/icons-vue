<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pqq1pzbhq"/><path class="uwcbl6bui"/><circle class="g5vbm32li"/><circle class="xr65xs9xo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:snowplow" /></template>
<style>
.g5vbm32li {
  cx: 10.75px;
  cy: 18.75px;
  r: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pqq1pzbhq {
  d: path("M7.5 15.75v-3.5a1 1 0 0 1 1-1h1.25l1.85-3.5A1.5 1.5 0 0 1 12.93 7h3.32a1 1 0 0 1 1 1v3.25h2.5a1 1 0 0 1 1 1v3.5a1 1 0 0 1-1 1H8.5a1 1 0 0 1-1-1");
}

.uwcbl6bui {
  d: path("M14 7v4.25H9.75m-5 3H7.5m-4.75-4.5H4a.75.75 0 0 1 .7.5c.6 2.25.6 4.25 0 6.5a.75.75 0 0 1-.7.5H2.75Z");
}

.xr65xs9xo {
  cx: 18px;
  cy: 18.75px;
  r: 2px;
}

</style>
