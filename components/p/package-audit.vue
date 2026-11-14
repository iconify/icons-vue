<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lfj-y_dam"/><path class="vg6xi6bcy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:package-audit" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lfj-y_dam {
  d: path("M13.534 20.688L12 21.5L3.5 17V7L12 2.5L20.5 7v5.982");
}

.vg6xi6bcy {
  d: path("m3.5 7l8.5 4.5L20.5 7M12 11.5v6.4m0 .2v3.4m2.75-3.5l2 2L21 15.75");
}

</style>
