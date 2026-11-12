<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a2aqw9y_p"/><path class="ty65c8klf"/><path class="ftbpoxdwt"/><path class="n9acjza5y"/><path class="lrz_m4wmq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:signal-high-broken" /></template>
<style>
.a2aqw9y_p {
  d: path("M3 20H3.0001");
}

.ftbpoxdwt {
  d: path("M12 20V12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lrz_m4wmq {
  d: path("M16.5 11V8");
}

.n9acjza5y {
  d: path("M16.5 20V15");
}

.ty65c8klf {
  d: path("M7.5 20V16");
}

</style>
