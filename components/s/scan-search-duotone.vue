<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qjql2tbsq"/><path class="if2h_hcma"/><path clip-rule="evenodd" class="ki4iswmtp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scan-search-duotone" /></template>
<style>
.if2h_hcma {
  d: path("M13.1213 13.1213L16 16");
}

.ki4iswmtp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15 11C15 13.2091 13.2091 15 11 15C8.7909 15 7 13.2091 7 11C7 8.7909 8.7909 7 11 7C13.2091 7 15 8.7909 15 11Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qjql2tbsq {
  stroke-opacity: 0.4;
  d: path("M3 8V6C3 4.34315 4.34315 3 6 3H8M16 3H18C19.6569 3 21 4.34315 21 6V8M21 16V18C21 19.6569 19.6569 21 18 21H16M8 21H6C4.34315 21 3 19.6569 3 18V16");
}

</style>
