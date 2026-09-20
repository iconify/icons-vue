<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f-x5yl3mg"/><path class="usiycnb-x"/><path class="hwv-lccbz"/><path class="xyhj-ubbr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:parser-outline-regular" /></template>
<style>
.f-x5yl3mg {
  d: path("M2 12h11");
}

.hwv-lccbz {
  d: path("M13 7h7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.usiycnb-x {
  d: path("M13 7v10");
}

.xyhj-ubbr {
  d: path("M13 17h7");
}

</style>
