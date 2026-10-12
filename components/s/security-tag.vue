<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="pap2ucgrx"/><path class="yu5lnvgmq"/><circle class="o80478h4m"/><path class="j4f4djbzt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:security-tag" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j4f4djbzt {
  d: path("M6.25 14h4");
}

.o80478h4m {
  cx: 15.5px;
  cy: 14px;
  r: 1.75px;
}

.pap2ucgrx {
  width: 18.5px;
  height: 8.5px;
  x: 2.75px;
  y: 9.75px;
  rx: 4.25px;
}

.yu5lnvgmq {
  d: path("M15.5 3.75v6");
}

</style>
