<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="wv5f_1brg"/><path class="yqkfkfb2m"/><circle class="u978tybzz"/><circle class="tyhetpb4e"/><circle class="uxmu2ccyb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:org-chart" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tyhetpb4e {
  cx: 12px;
  cy: 18.75px;
  r: 2.25px;
}

.u978tybzz {
  cx: 5px;
  cy: 18.75px;
  r: 2.25px;
}

.uxmu2ccyb {
  cx: 19px;
  cy: 18.75px;
  r: 2.25px;
}

.wv5f_1brg {
  cx: 12px;
  cy: 5.25px;
  r: 2.5px;
}

.yqkfkfb2m {
  d: path("M12 7.75v8.75m-7 0v-4A1.5 1.5 0 0 1 6.5 11h11a1.5 1.5 0 0 1 1.5 1.5v4");
}

</style>
