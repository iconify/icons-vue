<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vy_uxvzcu"/><path class="u3gisth2j"/><circle class="kr9czaceo"/><path class="ihvqhub0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:secom-safety-check-report" /></template>
<style>
.ihvqhub0d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 2.5l18.62 10.75v21.5L24 45.5L5.38 34.75v-21.5z");
}

.kr9czaceo {
  cx: 28.917px;
  cy: 28.31px;
  r: 3.336px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.u3gisth2j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.342 17.203c-3.278 4.1-7.148 4.217-9.317 2.413c-3.479-2.893 1.693-8.801 6.695-8.801s2.88 5.545-7.709 5.545M8.954 31.646h3.115c.734 0 1.325-.591 1.325-1.326v-.685c0-.734-.59-1.325-1.325-1.325h-1.79a1.323 1.323 0 0 1-1.325-1.326V26.3c0-.734.59-1.325 1.325-1.325h3.115m5.236-.002h-3.557m3.557 3.337h-3.557v3.336h3.557m6.41-.447a3.336 3.336 0 1 1 0-5.778");
}

.vy_uxvzcu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.546 23.116h32.909V14.5L24 5L7.546 14.5zm.001 10.386h32.907L24.003 43zm24.794-8.53l3.353 6.672l3.354-6.662v6.662");
}

</style>
