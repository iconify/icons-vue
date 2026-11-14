<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o72zbacef"/><path class="hc4ab_bcy"/><path class="wk0judr2g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:statement-kyc-form" /></template>
<style>
.hc4ab_bcy {
  d: path("M9.25 5.5h2.5a1.75 1.75 0 0 1 1.75 1.75v3A1.75 1.75 0 0 1 11.75 12h-2.5a1.75 1.75 0 0 1-1.75-1.75v-3A1.75 1.75 0 0 1 9.25 5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o72zbacef {
  d: path("M8.875 2.5h6.25A4.375 4.375 0 0 1 19.5 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375h-6.25A4.375 4.375 0 0 1 4.5 17.125V6.875A4.375 4.375 0 0 1 8.875 2.5");
}

.wk0judr2g {
  d: path("M9.25 7.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0M8.75 12c.25-1.25 3.25-1.25 3.5 0M7.5 15h9m-9 3.25H13");
}

</style>
