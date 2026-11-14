<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tuqd0mbvm"/><path class="neqw35bpn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-dentist" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.neqw35bpn {
  d: path("M7 9c0-1.5 1-2.25 2.75-2");
}

.tuqd0mbvm {
  d: path("M7 3.5c-2.5 0-3.5 2-3.25 4.5S5.5 12 6 14l1.25 5.5c.25 1.25 1.75 1.25 2 0l1-4.5c.25-1 3.25-1 3.5 0l1 4.5c.25 1.25 1.75 1.25 2 0L18 14c.5-2 2-3.5 2.25-6S19.5 3.5 17 3.5c-2 0-3 1.25-5 1.25S9 3.5 7 3.5");
}

</style>
