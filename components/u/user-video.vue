<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="v09w203dx"/><path class="kf_mvwa8r"/><rect class="v10qpcb0m"/><path class="v3jnlc9zi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:user-video" /></template>
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

.v09w203dx {
  cx: 9.5px;
  cy: 7.75px;
  r: 3.25px;
}

.v10qpcb0m {
  width: 3.75px;
  height: 4.25px;
  x: 14.75px;
  y: 9.5px;
  rx: 1px;
}

.v3jnlc9zi {
  d: path("m18.5 10.75l2.75-1.5V14l-2.75-1.5");
}

</style>
