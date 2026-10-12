<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sz57t6b-v"/><rect class="rruwowb6k"/><path class="u6kw3w_ie"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:window-blinds" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rruwowb6k {
  width: 15.5px;
  height: 13px;
  x: 4.25px;
  y: 3.75px;
  rx: 1px;
}

.sz57t6b-v {
  d: path("M2.75 3.75h18.5");
}

.u6kw3w_ie {
  d: path("M4.25 8h15.5m-15.5 4.5h15.5m-3.25 4.25v4.5");
}

</style>
