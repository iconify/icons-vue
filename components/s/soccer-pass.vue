<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oa_oaqnul"/><path class="bl-_tub_h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:soccer-pass" /></template>
<style>
.bl-_tub_h {
  d: path("m8.421 10.216l.54.42a1.5 1.5 0 0 1 .526 1.579l-.186.68A1.5 1.5 0 0 1 7.854 14h-.708a1.5 1.5 0 0 1-1.447-1.105l-.186-.68a1.5 1.5 0 0 1 .526-1.579l.54-.42a1.5 1.5 0 0 1 1.842 0M7.5 9.5v-3m2.25 4.75l3-1M9 14l1.75 2.5M6 14l-1.75 2.5m1-5.25l-3-1M15.75 12h5.75m-3-3l3 3l-3 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oa_oaqnul {
  d: path("M2 12a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

</style>
