<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n_evesvcy"/><path class="ovf4rgbwp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:office-building" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n_evesvcy {
  d: path("M4.25 6h15.5a1.75 1.75 0 0 1 1.75 1.75v12a1.75 1.75 0 0 1-1.75 1.75H4.25a1.75 1.75 0 0 1-1.75-1.75v-12A1.75 1.75 0 0 1 4.25 6M6 6V3h5v3m4.5 0V2.5m-10 7h2m3.5 0h2m3.5 0h2M5.5 13h2m3.5 0h2m3.5 0h2");
}

.ovf4rgbwp {
  d: path("M10 21.5v-5h4v5");
}

</style>
