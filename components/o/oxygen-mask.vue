<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vm2auenci"/><path class="v_mmj0bvv"/><path class="d0orvvtll"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:oxygen-mask" /></template>
<style>
.d0orvvtll {
  d: path("M19.75 18.25v3.25m-3.5-10L10 9.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v_mmj0bvv {
  fill: currentColor;
  d: path("M16.5 9.5c3.5-.5 5.25 2 5.25 4.5c0 2.75-2 4.5-5 4.75c-1-3-1-6.25-.25-9.25");
}

.vm2auenci {
  d: path("M8 21.5v-4c-2.5-1.75-3.5-4.25-3.5-7C4.5 6.25 7.75 3 12 3c2.86 0 5.208 1.406 6.315 3.669M15 20.926v.574");
}

</style>
