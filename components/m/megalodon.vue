<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="h27yupbhw"/><path class="wl2ek7bvl"/><ellipse transform="rotate(-80.266 25.228 23.154)" class="lpye7isqj"/><path class="ekjp2mfyh"/><circle class="wkwzg6c3s"/><path class="kemgm9rwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:megalodon" /></template>
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

.ekjp2mfyh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.634 21.264c-2.536 3.614-2.824 8.682-2.824 13.792c1.403-4.416 2.316-6.564 4.283-7.684");
}

.h27yupbhw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.897 38.244C10.051 21.172 16.446 8.79 24 8.79c8.023 0 13.243 10.047 14.542 31.044");
}

.kemgm9rwo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.014 22.254l.327.227m-2.43 8.481l.243.001m-.068-1.728l.447.087m-.285-1.582l.733.138m-.459-1.597l.66.183m-.265-1.63l.625.171m-.139-1.497l.616.221");
}

.lpye7isqj {
  cx: 25.227px;
  cy: 23.154px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.261px;
  ry: 2.256px;
}

.wkwzg6c3s {
  cx: 25.326px;
  cy: 23.904px;
  r: 0.75px;
  fill: currentColor;
}

.wl2ek7bvl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.519 45.232c.456-13.052 2.467-24.208 5.291-30.622");
}

</style>
