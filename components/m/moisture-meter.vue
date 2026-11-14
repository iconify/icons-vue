<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gslmz47uy"/><path class="o2u9z0bzg"/><path class="ew3k9ubth"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:moisture-meter" /></template>
<style>
.ew3k9ubth {
  fill: currentColor;
  d: path("M12 6.75S10.75 8.25 10.75 9a1.25 1.25 0 0 0 2.5 0c0-.75-1.25-2.25-1.25-2.25");
}

.gslmz47uy {
  d: path("M10 2.5h4A3.5 3.5 0 0 1 17.5 6v5.5A3.5 3.5 0 0 1 14 15h-4a3.5 3.5 0 0 1-3.5-3.5V6A3.5 3.5 0 0 1 10 2.5M9.5 15v6.5m5-6.5v6.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o2u9z0bzg {
  d: path("M10.75 5h2.5A1.75 1.75 0 0 1 15 6.75v2.5A1.75 1.75 0 0 1 13.25 11h-2.5A1.75 1.75 0 0 1 9 9.25v-2.5A1.75 1.75 0 0 1 10.75 5");
}

</style>
