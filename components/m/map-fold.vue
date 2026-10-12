<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ybf4fibio"/><path class="nhlcfzbys"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:map-fold" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nhlcfzbys {
  d: path("M20 14.5h-4.75q-.75 0-.75.75V20q0 .75.53.22l5.19-5.19q.53-.53-.22-.53M6.5 17.25c1.75-2.5 1.25-5 4-5.75s3.75-2 4.5-3.25m0 0l2.5-1.75");
}

.ybf4fibio {
  d: path("M4.75 3.25h14.5q1.5 0 1.5 1.5V13q0 1.5-1.06 2.56l-4.13 4.13Q14.5 20.75 13 20.75H4.75q-1.5 0-1.5-1.5V4.75q0-1.5 1.5-1.5");
}

</style>
