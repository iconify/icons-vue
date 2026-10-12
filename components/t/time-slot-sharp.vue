<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="x3mwnw_kp"/><circle class="qhvrk_ymv"/><path class="sqcb-fb9g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:time-slot-sharp" /></template>
<style>
.qhvrk_ymv {
  cx: 8.25px;
  cy: 12px;
  r: 3px;
}

.sqcb-fb9g {
  d: path("M8.25 10.5V12l1 .75m5-2.5h3.5m-3.5 3.5h2");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x3mwnw_kp {
  d: path("M2.75 6h18.5v12H2.75z");
}

</style>
