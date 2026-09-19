<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uj2f3_bzo"/><path class="gsn-e4bkp"/><circle class="cpk0fnbgt"/><path class="f4bhf7tgt"/><path class="ln4-cdsda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nethunter" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.f4bhf7tgt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.95 25.08l.841.842M33.8 21.015c-6.84-9.364-13.682-10.514-18.224-11.58");
}

.gsn-e4bkp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.684 34.253c0-4.266-7.837-6.173-7.837-10.715c0-2.467 1.514-2.635 3.59-2.635s5.046 1.962 6.392 2.86c0 0-.112 2.019.729 2.691s5.439 2.243 8.13 5.608l3.14-2.075s-3.588-.224-5.495-2.607l.73-.701l-2.692-4.599l-2.692.56a11.46 11.46 0 0 0-10.444-6.111c-7.023 0-6.627 8.802-5.93 10.71c.694 1.9 4.15 5.032 4.15 6.898");
}

.ln4-cdsda {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.55 16.948A8.8 8.8 0 0 0 24 14.566m-1.765 1.963a4.84 4.84 0 0 0-2.117-1.149m-.926 1.875a4.6 4.6 0 0 0-2.41.255m0 2.523a4.2 4.2 0 0 0-1.99.814M16 23.25a1.82 1.82 0 0 0-1.21 1.354");
}

.uj2f3_bzo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.666 37.58a40.42 40.42 0 0 0-33.333 0");
}

</style>
