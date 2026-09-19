<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uihwdqbsf"/><path class="l55lmtueq"/><circle class="guh0-8b0d"/><circle class="kuaddr-uz"/><path class="ymdgc9czu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:my-oldboy-1" /></template>
<style>
.guh0-8b0d {
  cx: 29.657px;
  cy: 30.659px;
  r: 1.096px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.kuaddr-uz {
  cx: 33.149px;
  cy: 28.446px;
  r: 1.096px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.l55lmtueq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.177 22.672l12.215-3.2l-2.903-10.921l-12.173 3.248zm16.847-2.697c.15.664-.35 1.065-.927 1.529v-.001a31.07 31.07 0 0 1-18.201 4.773c-.702-.075-1.353-.226-1.53-.89m7.505 9.624l-1.118-4.276m-1.578 2.696l4.275-1.117");
}

.uihwdqbsf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.8 38.511a28.04 28.04 0 0 1-18.594 4.866a1.71 1.71 0 0 1-1.396-1.074l-8.283-31.58a1.075 1.075 0 0 1 .763-1.311l18.605-4.877a1.075 1.075 0 0 1 1.31.763l8.272 31.57a1.6 1.6 0 0 1-.677 1.644Z");
}

.ymdgc9czu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.887 37.92l1.59-.419m1.697-.44l1.579-.419");
}

</style>
