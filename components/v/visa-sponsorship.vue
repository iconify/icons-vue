<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ekf2s55jf"/><path class="n3a9kub3b"/><path class="cdcd-9b6b"/><path class="qma-j37_v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:visa-sponsorship" /></template>
<style>
.cdcd-9b6b {
  d: path("M10.25 6.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

.ekf2s55jf {
  d: path("M2.5 15H6l4 2.5h4.25a1.25 1.25 0 0 1 0 2.5H9.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n3a9kub3b {
  d: path("M2.5 21.5H13l7.25-4.75c1-.75.25-2.25-1-1.75l-3.75 2.5M9.75 2h5.5A1.75 1.75 0 0 1 17 3.75v7.5A1.75 1.75 0 0 1 15.25 13h-5.5A1.75 1.75 0 0 1 8 11.25v-7.5A1.75 1.75 0 0 1 9.75 2");
}

.qma-j37_v {
  d: path("M11.5 6.5a1 2.25 0 1 0 2 0a1 2.25 0 1 0-2 0m-1.25 0h4.5m-4.5 4.5h4.5");
}

</style>
