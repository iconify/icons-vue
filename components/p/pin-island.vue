<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ss27qccah"/><path class="nzlepgbdd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-island" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nzlepgbdd {
  d: path("M12.5 17.5C12.5 13 12 9 10 6m0 0C8 3.5 5 3.5 3.5 6M10 6c2.5-3 6.5-3 9-.5M10 6c3.5 0 6 2 6.5 5.5");
}

.ss27qccah {
  d: path("M3.5 20c2.5-3.5 14.5-3.5 17 0Z");
}

</style>
