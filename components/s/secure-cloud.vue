<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i1u9r6bcs"/><rect class="jw3yeibai"/><path class="rma8_o41f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:secure-cloud" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i1u9r6bcs {
  d: path("M6.75 19.85a4 4 0 0 1-.55-7.96a5.75 5.75 0 0 1 10.65-1.39a4.5 4.5 0 0 1-.6 9.35Z");
}

.jw3yeibai {
  width: 6px;
  height: 4px;
  x: 9px;
  y: 13.5px;
  rx: 1.25px;
}

.rma8_o41f {
  d: path("M10.5 13.5v-1a1.5 1.5 0 0 1 3 0v1");
}

</style>
