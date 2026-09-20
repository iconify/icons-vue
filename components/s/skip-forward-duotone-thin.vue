<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="am-0fac9k"/><path class="bi4el8ygv"/><path class="swmt31b1p"/><path class="gtsw5xviq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:skip-forward-duotone-thin" /></template>
<style>
.am-0fac9k {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m6 5 7 7 -7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bi4el8ygv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gtsw5xviq {
  d: path("M17 5v14");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.swmt31b1p {
  d: path("m6 5 7 7 -7 7");
}

</style>
