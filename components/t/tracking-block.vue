<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="d8mt2_n-r"/><path class="h0dn49byt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tracking-block" /></template>
<style>
.d8mt2_n-r {
  cx: 12px;
  cy: 12px;
  r: 6.25px;
}

.h0dn49byt {
  d: path("M12 2.75V5m0 14v2.25M2.75 12H5m14 0h2.25M7.6 7.6l8.8 8.8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
