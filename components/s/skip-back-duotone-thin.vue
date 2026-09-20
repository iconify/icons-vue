<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gsozejbon"/><path class="lf5f-7bvs"/><path class="e80on1hgs"/><path class="azgrucbqu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:skip-back-duotone-thin" /></template>
<style>
.azgrucbqu {
  d: path("M7 5v14");
}

.e80on1hgs {
  d: path("m18 5 -7 7 7 7");
}

.gsozejbon {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m18 5 -7 7 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lf5f-7bvs {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
