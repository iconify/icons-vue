<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v39ujbbee"/><path class="oha9oq5od"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:map-player-arrow" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oha9oq5od {
  d: path("m13.056 9.339l-3.545 1.379a.604.604 0 0 0 .114 1.157l1.08.191a1.5 1.5 0 0 1 1.219 1.23l.201 1.204a.698.698 0 0 0 1.323.175l1.515-3.314a1.5 1.5 0 0 0-1.907-2.022");
}

.v39ujbbee {
  d: path("m3.697 5.101l4.289-1.43a1.75 1.75 0 0 1 1.035-.022l5.958 1.702a1.75 1.75 0 0 0 1.035-.022l3.183-1.061a1.75 1.75 0 0 1 2.303 1.66v11.311a1.75 1.75 0 0 1-1.197 1.66l-4.289 1.43a1.75 1.75 0 0 1-1.035.022l-5.958-1.702a1.75 1.75 0 0 0-1.035.022l-3.183 1.061a1.75 1.75 0 0 1-2.303-1.66V6.761a1.75 1.75 0 0 1 1.197-1.66");
}

</style>
