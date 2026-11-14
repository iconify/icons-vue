<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tf_s6-bhv"/><path class="ouolbhyoz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ph-strip" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ouolbhyoz {
  d: path("m14.33 2.867l.47.171a1.75 1.75 0 0 1 1.046 2.243l-3.933 10.806a1.75 1.75 0 0 1-2.243 1.046l-.47-.171a1.75 1.75 0 0 1-1.046-2.243l3.933-10.806a1.75 1.75 0 0 1 2.243-1.046m-3.953 5.744l3.759 1.368m-4.699 1.216l3.758 1.368m-4.699 1.216l3.759 1.369");
}

.tf_s6-bhv {
  d: path("M5 10v9a2.5 2.5 0 0 0 2.5 2.5h9A2.5 2.5 0 0 0 19 19v-9");
}

</style>
