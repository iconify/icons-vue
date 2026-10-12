<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="jh8sg_bol"/><path class="i78zpep2n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:voucher-gift" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i78zpep2n {
  d: path("M8.25 5.75v12.5m-5.5-7h18.5m-13 0c-.75-3-3-3.75-3-1.25c0 1.5 1.75 1.25 3 1.25c.75-3 3-3.75 3-1.25c0 1.5-1.75 1.25-3 1.25");
}

.jh8sg_bol {
  width: 18.5px;
  height: 12.5px;
  x: 2.75px;
  y: 5.75px;
  rx: 2px;
}

</style>
