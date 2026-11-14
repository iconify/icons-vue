<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tcejqlbgw"/><path class="a1d_fdc0s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tab-back" /></template>
<style>
.a1d_fdc0s {
  d: path("m11.5 9l-3 3l3 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tcejqlbgw {
  d: path("M2.5 18.5h2v-11A2.5 2.5 0 0 1 7 5h10a2.5 2.5 0 0 1 2.5 2.5v11h2m-6-6.5h-7");
}

</style>
