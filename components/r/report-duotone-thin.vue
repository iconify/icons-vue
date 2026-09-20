<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yxow7abeb"/><path class="abnm6smsv"/><path class="a5uqb5btg"/><path class="r-3ib9fxz"/><path class="i4l6z3b8k"/><path class="l1jjkky7x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:report-duotone-thin" /></template>
<style>
.a5uqb5btg {
  d: path("M9 14v4");
}

.abnm6smsv {
  d: path("M13 3H6v18h12V8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i4l6z3b8k {
  d: path("M15 13v5");
}

.l1jjkky7x {
  d: path("M8 18h8");
}

.r-3ib9fxz {
  d: path("M12 11v7");
}

.yxow7abeb {
  fill: currentColor;
  d: path("M13 3H6v18h12V8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
