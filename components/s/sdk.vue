<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wztday45h"/><path class="f10gkabwo"/><path class="y7450-nqs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sdk" /></template>
<style>
.f10gkabwo {
  d: path("m4.75 8.75l.36-.841A1.5 1.5 0 0 1 6.489 7h11.022a1.5 1.5 0 0 1 1.379.909l.36.841a1.255 1.255 0 0 1-1.154 1.75H5.904A1.255 1.255 0 0 1 4.75 8.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wztday45h {
  d: path("M6 10.5h12a3.5 3.5 0 0 1 3.5 3.5v3a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 17v-3A3.5 3.5 0 0 1 6 10.5");
}

.y7450-nqs {
  d: path("M9 7V5.5A1.5 1.5 0 0 1 10.5 4h3A1.5 1.5 0 0 1 15 5.5V7m-5 6.25L7.75 15.5L10 17.75m4-4.5l2.25 2.25L14 17.75");
}

</style>
