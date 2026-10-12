<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fswp1xb2h"/><circle class="a9v2pgbhx"/><circle class="l4apx-b4t"/><circle class="yj9-2ib_t"/><circle class="bqx8eybot"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:moon-rock" /></template>
<style>
.a9v2pgbhx {
  cx: 13px;
  cy: 11.5px;
  r: 2.75px;
}

.bqx8eybot {
  cx: 9px;
  cy: 9px;
  r: 0.75px;
}

.fswp1xb2h {
  d: path("m4.51 10.77l2.23-3.79q1.01-1.73 2.98-2.07l3.31-.57Q15 4 16.45 5.38l2.85 2.74q1.45 1.38 1.15 3.36l-.65 4.29q-.3 1.98-2.18 2.67l-3.74 1.37q-1.88.69-3.78.08l-3.2-1.03q-1.9-.61-2.4-2.55L4 14.44q-.5-1.94.51-3.67");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l4apx-b4t {
  cx: 8px;
  cy: 14.5px;
  r: 1px;
}

.yj9-2ib_t {
  cx: 15.5px;
  cy: 16.75px;
  r: 0.75px;
}

</style>
