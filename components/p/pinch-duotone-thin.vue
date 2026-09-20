<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hrjv8acbp"/><path class="bqgbkybbd"/><path class="mc2ku49ax"/><path class="i99bplbhq"/><path class="fpxzcl19b"/><path class="m3uk2nwvd"/><path class="v8mti3bcl"/><path class="m_x-fjbot"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pinch-duotone-thin" /></template>
<style>
.bqgbkybbd {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 5.5V9H5.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fpxzcl19b {
  d: path("m3 3 6 6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hrjv8acbp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 3 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i99bplbhq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 18.5V15h3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m_x-fjbot {
  d: path("M15 18.5V15h3.5");
}

.m3uk2nwvd {
  d: path("M9 5.5V9H5.5");
}

.mc2ku49ax {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m21 21 -6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v8mti3bcl {
  d: path("m21 21 -6 -6");
}

</style>
