<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i1fv66b2f"/><path class="iem2jlb_f"/><path class="k4mnq_b5y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-reef" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i1fv66b2f {
  d: path("M12 22c-3.5-2.5-9-6.5-9-11a9 9 0 0 1 18 0c0 4.5-5.5 8.5-9 11");
}

.iem2jlb_f {
  d: path("M12 14.5V11L9.5 8.5L7.75 6.75M12 11l2.5-2.5l1.75-1.75M9.5 8.5l1-2.5m4 2.5l-1-2.5");
}

.k4mnq_b5y {
  d: path("M8.5 14.5q1.75-1 3.5 0t3.5 0");
}

</style>
