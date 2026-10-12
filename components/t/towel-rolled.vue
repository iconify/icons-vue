<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f03zozbci"/><circle class="ng7y6b4ns"/><path class="yg_clqbut"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:towel-rolled" /></template>
<style>
.f03zozbci {
  d: path("M8 6.75h11A2.25 2.25 0 0 1 21.25 9v6A2.25 2.25 0 0 1 19 17.25H8a5.25 5.25 0 0 0 0-10.5m8.5 0v10.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ng7y6b4ns {
  cx: 8px;
  cy: 12px;
  r: 5.25px;
}

.yg_clqbut {
  d: path("M10.25 12A2.25 2.25 0 1 1 8 9.75");
}

</style>
