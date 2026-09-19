<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><ellipse class="ttftg8l_y"/><path class="mlmmbfb2g"/><path class="u6n-14r0t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sporcle" /></template>
<style>
.mlmmbfb2g {
  d: path("M26.457 36.688c5.48.362 9.4 1.87 9.4 3.616h0C35.857 42.345 30.55 44 24 44s-11.857-1.655-11.857-3.696c0-1.746 3.92-3.254 9.4-3.616m7.223-27.113q2.7 1.367 3.844 3.514");
}

.ttftg8l_y {
  cx: 24px;
  cy: 18.702px;
  rx: 14.898px;
  ry: 14.702px;
}

.u6n-14r0t {
  d: path("M21.906 33.308c1.423 2.717-.018 4.745-4.323 5.496c0 0 1.376 1.605 6.417 1.605m2.094-7.101c-1.423 2.717.018 4.745 4.323 5.496c0 0-1.376 1.605-6.417 1.605");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
