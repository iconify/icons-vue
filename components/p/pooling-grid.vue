<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="jje8784mt"/><path class="c6-j2cbgw"/><rect class="ees8h_0xt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pooling-grid" /></template>
<style>
.c6-j2cbgw {
  d: path("M7.75 7v10m-5-5h10m1.5-2L16 12l-1.75 2");
}

.ees8h_0xt {
  width: 3.5px;
  height: 4px;
  x: 17.75px;
  y: 10px;
  rx: 1px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jje8784mt {
  width: 10px;
  height: 10px;
  x: 2.75px;
  y: 7px;
  rx: 2.5px;
}

</style>
