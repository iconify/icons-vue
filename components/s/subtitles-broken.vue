<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="tc6nfibcu"/><path class="ktpncgb0v"/><path class="jmn44onlx"/><path class="wy63pibnm"/><path class="wu6h5cbil"/><path class="sqxfocc0h"/><path class="lqjkhsbgy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:subtitles-broken" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jmn44onlx {
  d: path("M14 13H18");
}

.ktpncgb0v {
  d: path("M10 16H6");
}

.lqjkhsbgy {
  d: path("M6 13H7");
}

.sqxfocc0h {
  d: path("M18 16H16.5");
}

.tc6nfibcu {
  d: path("M2 12C2 15.7712 2 17.6569 3.17157 18.8284C4.34315 20 6.22876 20 10 20H14C17.7712 20 19.6569 20 20.8284 18.8284C22 17.6569 22 15.7712 22 12C22 8.22876 22 6.34315 20.8284 5.17157C19.6569 4 17.7712 4 14 4H10C6.22876 4 4.34315 4 3.17157 5.17157C2.51839 5.82475 2.22937 6.69989 2.10149 8");
}

.wu6h5cbil {
  d: path("M9.5 13H11.5");
}

.wy63pibnm {
  d: path("M14 16H12.5");
}

</style>
