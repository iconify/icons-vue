<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e5_oj5bzd"/><path class="kqhw4bchn"/><path class="ujv-g8b1c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:route-overview" /></template>
<style>
.e5_oj5bzd {
  d: path("m4.077 5.551l4.25-1.771a1.75 1.75 0 0 1 1.346 0l4.654 1.94a1.75 1.75 0 0 0 1.346 0l2.904-1.21A1.75 1.75 0 0 1 21 6.125v10.708a1.75 1.75 0 0 1-1.077 1.616l-4.25 1.771a1.75 1.75 0 0 1-1.346 0l-4.654-1.94a1.75 1.75 0 0 0-1.346 0l-2.904 1.21A1.75 1.75 0 0 1 3 17.875V7.167a1.75 1.75 0 0 1 1.077-1.616");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kqhw4bchn {
  d: path("M7 15c2.5-6.5 7.5.5 10-6");
}

.ujv-g8b1c {
  fill: currentColor;
  d: path("M16 9a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

</style>
