<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mg7aqnbsf"/><path class="o04kmobcg"/><path class="d8abqfbpc"/><path class="heav9sszs"/><path class="xyj-l9cjp"/><path class="bc072wkjn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:stratified-sample-outline-bold" /></template>
<style>
.bc072wkjn {
  d: path("M16 21a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.d8abqfbpc {
  d: path("M3 11h18");
}

.heav9sszs {
  d: path("M11 14.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.mg7aqnbsf {
  d: path("M3 4h18");
}

.o04kmobcg {
  d: path("M6 7.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xyj-l9cjp {
  d: path("M3 18h18");
}

</style>
