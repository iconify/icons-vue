<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="axunpew9w"/><path class="z20mkgk9u"/><circle class="at-tytbll"/><path class="or48bdcrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:paylib" /></template>
<style>
.at-tytbll {
  cx: 33.625px;
  cy: 24.074px;
  r: 0.75px;
  fill: currentColor;
}

.axunpew9w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.183 14.683c5.141 0 9.317 4.176 9.317 9.317a9.315 9.315 0 0 1-9.317 9.317A9.307 9.307 0 0 1 24.867 24a9.315 9.315 0 0 1 9.316-9.317m-10.968 9.961v3.14a2.333 2.333 0 0 1-2.326 2.327h0c-.698 0-1.28-.232-1.629-.698");
}

.or48bdcrs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.625 26.866v6.28m2.781-11.758a2.333 2.333 0 0 1 2.326-2.327h0a2.333 2.333 0 0 1 2.327 2.327V22.9a2.333 2.333 0 0 1-2.327 2.326h0a2.333 2.333 0 0 1-2.326-2.326m0 2.442v-9.93");
}

.z20mkgk9u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.215 20.69v3.838a2.333 2.333 0 0 1-2.326 2.326h0a2.333 2.333 0 0 1-2.327-2.326V20.69m-2.378 3.954a2.333 2.333 0 0 1-2.327 2.327h0a2.333 2.333 0 0 1-2.326-2.327v-1.512a2.333 2.333 0 0 1 2.326-2.326h0a2.333 2.333 0 0 1 2.327 2.326m0 3.839V20.69M4.5 24.644a2.333 2.333 0 0 0 2.326 2.327h0a2.333 2.333 0 0 0 2.327-2.327v-1.512a2.333 2.333 0 0 0-2.327-2.326h0A2.333 2.333 0 0 0 4.5 23.132m0-2.442v9.305m25.162-13.958v8.142c0 .698.465 1.163 1.163 1.163h.35");
}

</style>
