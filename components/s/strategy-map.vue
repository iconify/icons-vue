<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wvxidbnsz"/><circle class="x2ld5m6gw"/><path class="df_dombal"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:strategy-map" /></template>
<style>
.df_dombal {
  d: path("M10.75 5.5h4A3.25 3.25 0 0 1 18 8.75V19.5m-2.75-2.75L18 19.5l2.75-2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wvxidbnsz {
  d: path("m3.75 3.75l3.5 3.5m0-3.5l-3.5 3.5");
}

.x2ld5m6gw {
  cx: 5.5px;
  cy: 17.75px;
  r: 2.75px;
}

</style>
