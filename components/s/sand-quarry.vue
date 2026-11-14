<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ek2pqwf_t"/><path class="xcrdinb0q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sand-quarry" /></template>
<style>
.ek2pqwf_t {
  d: path("M2.5 21C4 15.5 7 10.5 10 10.5c1.25 0 2 1.25 2.5 2.75m5 1c1.5 1.75 3 4.25 4 6.75m-19 0h19M17 2.25l3.75 1.5M19 3l-3.25 9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xcrdinb0q {
  d: path("m14.909 11.611l1.457.537a1.717 1.717 0 0 1 1.009 2.227l-.413 1.073a1.75 1.75 0 0 1-.716.862l-1.124.692a1.643 1.643 0 0 1-2.372-.752l-.479-1.119a1.75 1.75 0 0 1-.04-1.278l.425-1.188a1.75 1.75 0 0 1 2.253-1.054");
}

</style>
