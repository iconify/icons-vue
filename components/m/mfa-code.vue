<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="ycnxyysrm"/><path class="i92xgwfig"/><rect class="v89_qk0ru"/><path class="wb1bcbceu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mfa-code" /></template>
<style>
.i92xgwfig {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 5.5h2.5M6.75 18h2.5");
}

.v89_qk0ru {
  width: 10.75px;
  height: 6.5px;
  x: 10.5px;
  y: 8.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.75px;
}

.wb1bcbceu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.25 12h.01m2.62 0h.01m2.61 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ycnxyysrm {
  width: 10.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.25px;
}

</style>
