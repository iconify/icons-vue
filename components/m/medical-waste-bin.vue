<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zdp03rzwn"/><path class="fkuq97bcx"/><path class="tr3-sac-d"/><path class="i5wpcse2u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:medical-waste-bin" /></template>
<style>
.fkuq97bcx {
  d: path("M17.434 2.952za1.25 1.25 0 0 1 .307 1.741l-1.434 2.048a1.25 1.25 0 0 1-1.741.307a1.25 1.25 0 0 1-.307-1.741l1.434-2.048a1.25 1.25 0 0 1 1.741-.307M13.75 8l-1 1.5m.75 3.5a1.75 1.75 0 1 1-3 0a1.25 1.25 0 0 0 3 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i5wpcse2u {
  d: path("M8.5 15.75A1.75 1.75 0 1 1 9.75 18a1.25 1.25 0 0 0-1.25-2.25");
}

.tr3-sac-d {
  d: path("M14.25 18a1.75 1.75 0 1 1 1.25-2.25A1.25 1.25 0 0 0 14.25 18");
}

.zdp03rzwn {
  d: path("M7.625 10.5h8.75A2.625 2.625 0 0 1 19 13.125v5.75a2.625 2.625 0 0 1-2.625 2.625h-8.75A2.625 2.625 0 0 1 5 18.875v-5.75A2.625 2.625 0 0 1 7.625 10.5m-3.125 0h15L18.25 7L6 8.5ZM9.75 9l4.5-.5");
}

</style>
