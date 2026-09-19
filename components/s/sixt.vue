<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="llokitadl"/><path class="ux-cf3egw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sixt" /></template>
<style>
.llokitadl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4M20.472 23.056v6.624m4.276-7.879l5.22 7.879m0-10.598L22.947 29.68m7.032-10.598H37M33.49 29.68V19.082");
}

.ux-cf3egw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.21 28.519c.65.846 1.465 1.16 2.598 1.16h1.57a2.644 2.644 0 0 0 2.643-2.643v-.011a2.644 2.644 0 0 0-2.644-2.644h-1.73A2.647 2.647 0 0 1 11 21.734h0a2.65 2.65 0 0 1 2.652-2.652h1.56c1.134 0 1.95.315 2.6 1.161m7.841-3.923c-.836 2.284-2.173 4.087-5.18 4.087");
}

</style>
