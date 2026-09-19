<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lav4q8hhk"/><circle class="cpk0fnbgt"/><path class="ghg60pbel"/><circle class="x8ehlgbiu"/><path class="wqikblvec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pagekeeper" /></template>
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

.ghg60pbel {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.164 3.051v8.653c0 2.757 2.156 4.568 4.582 4.615c2.367.045 4.724-1.462 4.724-4.42V2.97M18.41 21.32h10.58m-10.58 4.36h10.58");
}

.lav4q8hhk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.41 34.28h10.58m-10.58-4.4h10.58");
}

.wqikblvec {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.47 9.177c3.256.017 5.096 1.311 5.096 4.25v22.425c.044 3.92-4.342 8.231-9.866 2.142c-5.79 5.887-10.274 1.528-10.202-2.535V13.89c0-4.007 3.002-4.714 5.666-4.714");
}

.x8ehlgbiu {
  cx: 23.711px;
  cy: 11.32px;
  r: 1.4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
