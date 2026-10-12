<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="jg7xt1_6k"/><path class="ygmy9t_vg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sleep-schedule" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jg7xt1_6k {
  cx: 10px;
  cy: 14px;
  r: 7.25px;
}

.ygmy9t_vg {
  d: path("M10 10.25V14l2.5 1.75M16 3.25h4l-4 4.5h4");
}

</style>
