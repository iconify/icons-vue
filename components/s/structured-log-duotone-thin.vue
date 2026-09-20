<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ots31sbwo"/><path class="jd_dotbnq"/><path class="kyzykiukp"/><path class="l15o95bip"/><path class="zm28o9bsg"/><path class="j61i2zz4t"/><path class="c6uw-ccfl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:structured-log-duotone-thin" /></template>
<style>
.c6uw-ccfl {
  d: path("M7 14h10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j61i2zz4t {
  d: path("M12.5 10H17");
}

.jd_dotbnq {
  d: path("M6 2h12a2 2 0 0 1 2 2v15l-2 -2 -2 2 -2 -2 -2 2 -2 -2 -2 2 -2 -2 -2 2V4a2 2 0 0 1 2 -2");
}

.kyzykiukp {
  d: path("M7 6h3");
}

.l15o95bip {
  d: path("M12.5 6H17");
}

.ots31sbwo {
  fill: currentColor;
  d: path("M6 2h12a2 2 0 0 1 2 2v15l-2 -2 -2 2 -2 -2 -2 2 -2 -2 -2 2 -2 -2 -2 2V4a2 2 0 0 1 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zm28o9bsg {
  d: path("M7 10h3");
}

</style>
