<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="trv9mgb9o"/><path class="oyt9u7ueo"/><circle class="dxmh3lbzl"/><path class="epv2nm1df"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:payroll" /></template>
<style>
.dxmh3lbzl {
  cx: 17.25px;
  cy: 13px;
  r: 4px;
}

.epv2nm1df {
  d: path("M18.38 12.02c-.21-.45-.62-.75-1.12-.75c-.67 0-1.17.39-1.17.86c0 1.22 2.34.61 2.34 1.78c0 .49-.5.83-1.17.83c-.52 0-.96-.28-1.14-.73");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oyt9u7ueo {
  d: path("M3.5 19.75h8a.75.75 0 0 0 .75-.75c0-3-2.1-5.25-4.75-5.25S2.75 16 2.75 19a.75.75 0 0 0 .75.75");
}

.trv9mgb9o {
  cx: 7.5px;
  cy: 7.25px;
  r: 3px;
}

</style>
