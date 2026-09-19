<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lhpsac54i"/><circle class="lg0iq-b1c"/><path class="pb6s3zbhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sbt" /></template>
<style>
.lg0iq-b1c {
  cx: 28.751px;
  cy: 24.225px;
  r: 4.556px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.lhpsac54i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.056 28.781v-9.112M2.5 24.225h9.112m3.231 3.787c.627.527 1.305.769 2.827.769h.772a2.276 2.276 0 0 0 2.273-2.278h0a2.276 2.276 0 0 0-2.273-2.278h-1.543a2.276 2.276 0 0 1-2.273-2.278h0a2.276 2.276 0 0 1 2.273-2.278h.771c1.523 0 2.2.242 2.828.769m16.734-3.606v10.23c0 .95.77 1.719 1.719 1.719h.516m-4.041-9.112h3.611m-14.842 4.556v-9.198");
}

.pb6s3zbhr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.223 31.773c3.029 7.142 10.105 12.153 18.351 12.153C36.58 43.926 45.5 35.004 45.5 24S36.579 4.074 25.574 4.074c-8.416 0-15.598 5.226-18.518 12.603");
}

</style>
