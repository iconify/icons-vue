<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wlgi4hbmg"/><path class="ilcs1-bgp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:spelling-bee" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ilcs1-bgp {
  d: path("M9.5 7.5C8 5 6 4.5 4.5 5.5c.5 2.5 2.5 3 5 2m5 0c1.5-2.5 3.5-3 5-2c-.5 2.5-2.5 3-5 2");
}

.wlgi4hbmg {
  d: path("M12 7c3.5 0 5.5 2.5 5.5 6c0 4-2.5 7-5.5 7s-5.5-3-5.5-7c0-3.5 2-6 5.5-6m-5.25 4.5h10.5m-10.75 4h11");
}

</style>
