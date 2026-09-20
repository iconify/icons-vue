<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yeodwlnkh"/><path class="fcpcpjxqg"/><path class="vcjsoxbsd"/><path class="r0_oskb4z"/><path class="yf_brbf0s"/><path class="hf_gtezns"/><path class="mg7aqnbsf"/><path class="o04kmobcg"/><path class="d8abqfbpc"/><path class="heav9sszs"/><path class="xyj-l9cjp"/><path class="bc072wkjn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:stratified-sample-duotone-thin" /></template>
<style>
.bc072wkjn {
  d: path("M16 21a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.d8abqfbpc {
  d: path("M3 11h18");
}

.fcpcpjxqg {
  fill: currentColor;
  d: path("M11 14.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.heav9sszs {
  d: path("M11 14.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hf_gtezns {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mg7aqnbsf {
  d: path("M3 4h18");
}

.o04kmobcg {
  d: path("M6 7.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.r0_oskb4z {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 4h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vcjsoxbsd {
  fill: currentColor;
  d: path("M16 21a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xyj-l9cjp {
  d: path("M3 18h18");
}

.yeodwlnkh {
  fill: currentColor;
  d: path("M6 7.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.yf_brbf0s {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 11h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
