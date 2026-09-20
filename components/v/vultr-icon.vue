<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":221};
const content = `<path class="chulr3pmk"/><path class="tddkordom"/><path class="r841kztfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:vultr-icon" /></template>
<style>
.chulr3pmk {
  fill: var(--svg-color--c9f4ff, #c9f4ff);
  d: path("M89.173 6.095A12.74 12.74 0 0 0 78.385 0H12.8C5.73 0 0 5.73 0 12.8c0 2.413.676 4.778 1.95 6.827l16.884 24.807l84.42-18.285z");
}

.r841kztfo {
  fill: var(--svg-color--007bfc, #007bfc);
  d: path("M34.255 68.937a13.04 13.04 0 0 1-1.158-11.459a12.86 12.86 0 0 1 12.19-8.168h65.342a12.8 12.8 0 0 1 10.85 6.096l58.696 93.074a12.9 12.9 0 0 1 1.95 6.827a13.1 13.1 0 0 1-1.95 6.826l-32.792 51.993a12.86 12.86 0 0 1-21.7 0zm165.303 29.745a12.86 12.86 0 0 0 21.7 0l11.275-17.86L254.05 46.69a12.9 12.9 0 0 0 1.95-6.827a13.1 13.1 0 0 0-1.95-6.827l-17.067-26.94A12.86 12.86 0 0 0 226.133 0H160.55a12.8 12.8 0 0 0-12.801 12.8a12.2 12.2 0 0 0 2.012 6.827z");
}

.tddkordom {
  fill: var(--svg-color--51b9ff, #51b9ff);
  d: path("M103.619 26.636a12.86 12.86 0 0 0-10.85-6.095H27.43A12.739 12.739 0 0 0 16.213 40.29l18.835 29.866l87.222-13.653z");
}

</style>
