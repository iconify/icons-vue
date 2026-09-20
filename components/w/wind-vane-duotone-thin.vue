<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rzvp5cbis"/><path class="az1hpy9gr"/><path class="xslfg2evh"/><path class="t6hbaucfr"/><path class="l0v-b4kbr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wind-vane-duotone-thin" /></template>
<style>
.az1hpy9gr {
  d: path("M12 9v12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l0v-b4kbr {
  d: path("M8 12h8");
}

.rzvp5cbis {
  fill: currentColor;
  d: path("m6 6 3 -3h3v6H9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.t6hbaucfr {
  d: path("m6 6 3 -3h3v6H9Z");
}

.xslfg2evh {
  d: path("M6 21h12");
}

</style>
