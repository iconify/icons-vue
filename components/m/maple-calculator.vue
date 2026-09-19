<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ll0g54h-q"/><path class="w6woambzd"/><circle class="c3f-hsbol"/><path class="g7x2o93yr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:maple-calculator" /></template>
<style>
.c3f-hsbol {
  cx: 24px;
  cy: 24px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.g7x2o93yr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.5V17m7 7h11.5M24 31v11.5M17 24H5.5m1.588-9.576h2.05l1.916 4.575l3.223-9.668h8.114M12.252 30.866c-2.355.011-2.176 1.242-2.614 3.346c-.439 2.102-.085 3.924-2.66 4.069m1.262-4.248h2.66m27.887-2.098h-6.92m4.598 0l.045 3.81c-.024 2.515 1.763 2.263 2.322 1.08m-4.823-4.89c-.474 1.913.644 5.79-1.488 5.657");
}

.ll0g54h-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4");
}

.w6woambzd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.137 30.794s1.476 1.677 1.476 3.744s-1.476 3.743-1.476 3.743m-3.877-7.487s-1.475 1.677-1.475 3.744s1.475 3.743 1.475 3.743m3.365-5.709l-2.951 3.909m2.951 0l-2.951-3.909m24.81-19.82l-3.365 4.459m3.365 0l-3.365-4.459");
}

</style>
