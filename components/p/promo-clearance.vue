<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r3dkt3bqn"/><path class="xtytx-b5g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:promo-clearance" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r3dkt3bqn {
  d: path("M5.125 2.5h2.788a2.63 2.63 0 0 1 1.856.769l4.875 4.875a2.625 2.625 0 0 1 0 3.712l-2.788 2.788a2.625 2.625 0 0 1-3.712 0L3.269 9.769A2.63 2.63 0 0 1 2.5 7.913V5.125A2.625 2.625 0 0 1 5.125 2.5");
}

.xtytx-b5g {
  d: path("M5 6.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m13 8v7m-3-3l3 3l3-3");
}

</style>
