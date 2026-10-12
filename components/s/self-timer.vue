<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="cseut-bvw"/><path class="aidy_acxp"/><circle class="d4da7x21x"/><path class="exv899b0n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:self-timer" /></template>
<style>
.aidy_acxp {
  d: path("M12.75 10.25a2.75 2.75 0 1 1-5.5 0a2.75 2.75 0 1 1 5.5 0");
}

.cseut-bvw {
  width: 15px;
  height: 11px;
  x: 2.75px;
  y: 4.75px;
  rx: 2px;
}

.d4da7x21x {
  cx: 16.75px;
  cy: 16.75px;
  r: 4.5px;
}

.exv899b0n {
  d: path("M16.75 14.75v2l1.25 1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
