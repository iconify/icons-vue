<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse transform="rotate(-66.922 30.923 7.17)" class="m1rbffbch"/><path class="coumhybtc"/><path class="z0fez-r0m"/><ellipse transform="rotate(-81.355 26.187 18.94)" class="ihlej_bqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vins-millesimes" /></template>
<style>
.coumhybtc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.493 39.446c2.01 1.178 3.22 2.539 2.867 3.366c-.457 1.072-3.337.868-6.432-.45s-5.237-3.255-4.78-4.327c.353-.827 2.172-.897 4.414-.264M36.903 9.718c-.106 10.174-4.527 21.153-14.304 16.987s-4.92-14.959 2.344-22.083");
}

.ihlej_bqy {
  cx: 26.187px;
  cy: 18.941px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.134px;
  ry: 8.947px;
}

.m1rbffbch {
  cx: 30.923px;
  cy: 7.17px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.865px;
  ry: 6.5px;
}

.z0fez-r0m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.229 27.275s-3.843 5.77-4.738 12.171c-.42.367-.319 1.187-2.44.282s-1.461-1.398-1.488-1.955c3.997-5.08 5.497-11.848 5.497-11.848");
}

</style>
