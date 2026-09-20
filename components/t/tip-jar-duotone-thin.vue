<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fb6xkzb1k"/><path class="wvt4g8bjb"/><path class="g_k4bub3x"/><path class="guw4_4ovg"/><path class="r9il7jbjw"/><path class="gzes1rhcl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tip-jar-duotone-thin" /></template>
<style>
.fb6xkzb1k {
  fill: currentColor;
  d: path("M6 9h12v10a3 3 0 0 1 -3 3H9a3 3 0 0 1 -3 -3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.g_k4bub3x {
  d: path("M6 9h12v10a3 3 0 0 1 -3 3H9a3 3 0 0 1 -3 -3Z");
}

.guw4_4ovg {
  d: path("M8 9V4h8v5");
}

.gzes1rhcl {
  d: path("M12 13.5v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r9il7jbjw {
  d: path("M9 15.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.wvt4g8bjb {
  fill: currentColor;
  d: path("M9 15.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
