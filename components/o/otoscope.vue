<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="hwhw_o_ln"/><rect class="ky-wx4b3j"/><path class="ssq5ribgm"/><rect class="bppw_r_gh"/><path class="n35-x3bho"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:otoscope" /></template>
<style>
.bppw_r_gh {
  width: 4px;
  height: 10px;
  x: 8.5px;
  y: 11.25px;
  rx: 1.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hwhw_o_ln {
  width: 3.75px;
  height: 3.5px;
  x: 2.75px;
  y: 6.75px;
  rx: 1px;
}

.ky-wx4b3j {
  width: 8px;
  height: 5.5px;
  x: 6.5px;
  y: 5.75px;
  rx: 1.5px;
}

.n35-x3bho {
  d: path("M8.5 14.75h4m-4 3h4");
}

.ssq5ribgm {
  d: path("m15.23 6.41l5.29 1.18q.73.16.73.91t-.73.91l-5.29 1.18q-.73.16-.73-.59V7q0-.75.73-.59");
}

</style>
