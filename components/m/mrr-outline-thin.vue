<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ffw_pwyfz"/><path class="kfdmhd64i"/><path class="hqwqevb6s"/><path class="bu4zjnbek"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mrr-outline-thin" /></template>
<style>
.bu4zjnbek {
  d: path("M9.5 10H13");
}

.ffw_pwyfz {
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hqwqevb6s {
  d: path("M6.5 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.kfdmhd64i {
  d: path("m15 15 6 6");
}

</style>
