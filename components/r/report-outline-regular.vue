<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="abnm6smsv"/><path class="a5uqb5btg"/><path class="r-3ib9fxz"/><path class="i4l6z3b8k"/><path class="l1jjkky7x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:report-outline-regular" /></template>
<style>
.a5uqb5btg {
  d: path("M9 14v4");
}

.abnm6smsv {
  d: path("M13 3H6v18h12V8");
}

.i4l6z3b8k {
  d: path("M15 13v5");
}

.l1jjkky7x {
  d: path("M8 18h8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r-3ib9fxz {
  d: path("M12 11v7");
}

</style>
