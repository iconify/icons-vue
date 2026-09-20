<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r0_oskb4z"/><path class="hsnj9o-9y"/><path class="syr202grk"/><path class="f-kqc0bvh"/><path class="f3e5iccba"/><path class="mg7aqnbsf"/><path class="jkuojibnm"/><path class="h7bcztycq"/><path class="bhl_zu55p"/><path class="p9jmvgbqq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:spacer-duotone-thin" /></template>
<style>
.bhl_zu55p {
  d: path("M9.5 10.5 12 8l2.5 2.5");
}

.f-kqc0bvh {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9.5 10.5 12 8l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f3e5iccba {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9.5 13.5 12 16l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h7bcztycq {
  d: path("M12 8v8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hsnj9o-9y {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jkuojibnm {
  d: path("M3 20h18");
}

.mg7aqnbsf {
  d: path("M3 4h18");
}

.p9jmvgbqq {
  d: path("M9.5 13.5 12 16l2.5 -2.5");
}

.r0_oskb4z {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 4h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.syr202grk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
