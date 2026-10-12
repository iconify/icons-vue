<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sm9qir7hb"/><circle class="cibw8q46d"/><circle class="t2x7kg3eo"/><path class="tsqj-fcfp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:user-mask" /></template>
<style>
.cibw8q46d {
  cx: 8px;
  cy: 15px;
  r: 2.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sm9qir7hb {
  d: path("m7.25 8.25l1.5-4.5A1 1 0 0 1 9.7 3h4.6a1 1 0 0 1 .95.75l1.5 4.5Zm-4 0h17.5");
}

.t2x7kg3eo {
  cx: 16px;
  cy: 15px;
  r: 2.75px;
}

.tsqj-fcfp {
  d: path("M10.75 15h2.5");
}

</style>
