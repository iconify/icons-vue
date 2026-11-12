<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ik4yyycul"/><path class="v4tckp_mx"/><path class="dxz_62g8x"/><path class="uzj9wplpi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:screencast-linear" /></template>
<style>
.dxz_62g8x {
  d: path("M2 14C5.31371 14 8 16.6863 8 20");
}

.ik4yyycul {
  stroke-linejoin: round;
  d: path("M14 20C17.7712 20 19.6569 20 20.8284 18.8284C22 17.6569 22 15.7712 22 12C22 8.22876 22 6.34315 20.8284 5.17157C19.6569 4 17.7712 4 14 4H6.5C6.03566 4 5.80349 4 5.60793 4.01926C3.70882 4.20631 2.20631 5.70882 2.01926 7.60793C2 7.80349 2 8.03566 2 8.5");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uzj9wplpi {
  d: path("M2 17C3.65685 17 5 18.3431 5 20");
}

.v4tckp_mx {
  d: path("M2 11C6.97056 11 11 15.0294 11 20");
}

</style>
