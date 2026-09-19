<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><path id="SVGVy7CIGVG" class="ybj0mrt4o"/></defs><path class="t72_tibwq"/><path class="zp-jwzbuo"/><use href="#SVGVy7CIGVG" class="c-zrgpb5l"/><use href="#SVGVy7CIGVG" class="c-zrgpb5l"/><path class="iqsf85bnh"/><path class="x1bfmcbjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:moco" /></template>
<style>
.c-zrgpb5l {
  stroke-linecap: round;
  stroke-linejoin: round;
}

.iqsf85bnh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.698 32.087l10.745-3.128v-6.995l-1.55.77l2.682-5.446");
}

.t72_tibwq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.61 13.527l4.89-6.87l-35 10.759l5.886 3.785m24.223-7.674v20.37l-24.223 7.447m0 0V21.2");
}

.x1bfmcbjk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.575 17.288L19.83 20.416v6.995l1.55-.77l-2.682 5.446");
}

.ybj0mrt4o {
  fill: none;
  stroke: currentColor;
  d: path("M32.658 30.752v-16.72l-16.035 5.022");
}

.zp-jwzbuo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.624 19.054v16.719l16.034-5.022");
}

</style>
