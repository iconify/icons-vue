<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="t8yaf7baj"/><rect class="kx2ytbb5n"/><circle class="m7gj_g5yk"/><path class="hcv1ivbcs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:restroom-men" /></template>
<style>
.hcv1ivbcs {
  d: path("M17.5 9.25h.75q1 0 1.24.97l1.27 5.06q.24.97-.76.97h-4.25q-1 0-.76-.97l1.27-5.06q.24-.97 1.24-.97m.4 7v5m-6.15-18.5v18.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kx2ytbb5n {
  width: 4.5px;
  height: 12px;
  x: 4.25px;
  y: 9.25px;
  rx: 2.25px;
}

.m7gj_g5yk {
  cx: 17.9px;
  cy: 4.5px;
  r: 1.75px;
}

.t8yaf7baj {
  cx: 6.5px;
  cy: 4.5px;
  r: 1.75px;
}

</style>
