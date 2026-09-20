<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="se4mxf8ip"/><path class="acja6ya7a"/><path class="c30ujnbdh"/><path class="vn6-di86m"/><path class="zoz5ar7wf"/><path class="v0y09obth"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pocket-money-duotone-thin" /></template>
<style>
.acja6ya7a {
  fill: currentColor;
  d: path("M9 14a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.c30ujnbdh {
  d: path("M4 3v11a8 8 0 0 0 16 0V3Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.se4mxf8ip {
  fill: currentColor;
  d: path("M4 3v11a8 8 0 0 0 16 0V3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.v0y09obth {
  d: path("M12 12v4");
}

.vn6-di86m {
  d: path("M4 7h16");
}

.zoz5ar7wf {
  d: path("M9 14a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
