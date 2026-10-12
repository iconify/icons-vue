<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ob_3wxbim"/><rect class="hxctz3qvq"/><path class="v_ziurbxq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pastry-brush" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hxctz3qvq {
  width: 9px;
  height: 3px;
  x: 7.5px;
  y: 9.75px;
  rx: 1px;
}

.ob_3wxbim {
  width: 3.5px;
  height: 7px;
  x: 10.25px;
  y: 2.75px;
  rx: 1.75px;
}

.v_ziurbxq {
  d: path("M9 12.75L8 21m4-8.25V21m3-8.25L16 21");
}

</style>
