<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ebs-wtr1f"/><path class="bvt-woblq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minimize-broken" /></template>
<style>
.bvt-woblq {
  d: path("M22 2L15 9M15 3.14286V9H20.8571");
}

.ebs-wtr1f {
  d: path("M9 20.8571V15H3.14286M9 15L5.5 18.5M2 22L2.875 21.125");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
