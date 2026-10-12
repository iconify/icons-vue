<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s7y5_ybim"/><rect class="z6iawzb1t"/><path class="rcq9-1ntj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:secure-wifi" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rcq9-1ntj {
  d: path("M10.5 15.25V14a1.5 1.5 0 0 1 3 0v1.25");
}

.s7y5_ybim {
  d: path("M2.75 9a13 13 0 0 1 18.5 0M6 12.25a8.5 8.5 0 0 1 12 0");
}

.z6iawzb1t {
  width: 6px;
  height: 6px;
  x: 9px;
  y: 15.25px;
  rx: 1.25px;
}

</style>
