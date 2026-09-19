<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="y19wndg2g"/><ellipse class="p7koir00n"/><path class="c64v50b9o"/><path class="bs7eqgbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:y-yahoo" /></template>
<style>
.bs7eqgbax {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.704 37.367l13.931-6.04h9.523c2.02 0 3.655-3.28 3.655-7.327s-1.636-7.328-3.655-7.328h-9.523l-13.931-6.04m-4.228 9.816h5.994m-5.994 7.104h5.994");
}

.c64v50b9o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.085 37.231c-2.649 0-5.61-5.658-5.61-13.231s2.962-13.231 5.61-13.231s5.61 5.658 5.61 13.231s-2.962 13.231-5.61 13.231m19.637-5.903c2.019 0 3.655-3.281 3.655-7.328s-1.637-7.328-3.655-7.328m10.172 2.468h1.182c1.339 0 2.424 2.176 2.424 4.86s-1.085 4.86-2.424 4.86h-1.183");
}

.p7koir00n {
  cx: 11.085px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.585px;
  ry: 15.207px;
}

.y19wndg2g {
  cx: 10.476px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.772px;
  ry: 3.552px;
}

</style>
