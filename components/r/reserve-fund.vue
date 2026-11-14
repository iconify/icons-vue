<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hk72_73dl"/><path class="hwdc-y6jg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:reserve-fund" /></template>
<style>
.hk72_73dl {
  d: path("M19.487 10.967C18.541 9.403 17.096 7.897 15 6.5H9c-4.5 3-6 6.5-6 10c0 3 2 5 5 5h4.329M9 6.5L7 3h10l-2 3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hwdc-y6jg {
  d: path("M12.25 12.25C12 11.5 11.4 11 10.5 11c-1 0-1.75.6-1.75 1.5c0 1.75 3.5 1 3.5 3c0 .9-.75 1.5-1.75 1.5s-1.6-.5-1.75-1.25M10.5 10v1m0 6v1m6-4.25h3a1.5 1.5 0 0 1 1.5 1.5v5a1.5 1.5 0 0 1-1.5 1.5h-3a1.5 1.5 0 0 1-1.5-1.5v-5a1.5 1.5 0 0 1 1.5-1.5M18 16.5h.01M18 19.25h.01");
}

</style>
