<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yxd4266ui"/><path class="f7i5iq2xf"/><path class="qaia1d1wv"/><path class="wt9iv5biz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:terrain-duotone-thin" /></template>
<style>
.f7i5iq2xf {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m2 19 6 -6 3 3 5 -5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qaia1d1wv {
  d: path("m2 12 6 -6 3 3 5 -5 5 5");
}

.wt9iv5biz {
  d: path("m2 19 6 -6 3 3 5 -5 5 5");
}

.yxd4266ui {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m2 12 6 -6 3 3 5 -5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
