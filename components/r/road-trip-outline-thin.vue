<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t1w08ccuz"/><path class="g7ipnac6i"/><path class="icp673bbo"/><path class="pa9quik2g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:road-trip-outline-thin" /></template>
<style>
.g7ipnac6i {
  d: path("m21 20 -6 -6V5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.icp673bbo {
  d: path("M12 9v3");
}

.pa9quik2g {
  d: path("M12 16v3");
}

.t1w08ccuz {
  d: path("m3 20 6 -6V5");
}

</style>
