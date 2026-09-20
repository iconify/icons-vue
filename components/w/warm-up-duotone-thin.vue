<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vrx4z7bbq"/><path class="cdkjy4ble"/><path class="yurn2fb8b"/><path class="k4vr6d8iw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:warm-up-duotone-thin" /></template>
<style>
.cdkjy4ble {
  d: path("M9 3c1.5 3 4.5 4.5 4.5 8a4.5 4.5 0 1 1 -9 0C4.5 8 7 7.5 7 5.5 7.5 6 9 6 9 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k4vr6d8iw {
  d: path("m16 11 3 -3 3 3");
}

.vrx4z7bbq {
  fill: currentColor;
  d: path("M9 3c1.5 3 4.5 4.5 4.5 8a4.5 4.5 0 1 1 -9 0C4.5 8 7 7.5 7 5.5 7.5 6 9 6 9 3");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.yurn2fb8b {
  d: path("M19 20V8");
}

</style>
