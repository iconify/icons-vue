<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="h2k9w8b3k"/><circle class="ow552-bev"/><path class="lzfx1bbox"/><circle class="b-4223baq"/><path class="zpcsdlb2i"/><circle class="dpl8w9b6p"/><path class="ougufmpwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:metatrader-5" /></template>
<style>
.b-4223baq {
  cx: 9.658px;
  cy: 34.439px;
  r: 4.658px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.dpl8w9b6p {
  cx: 38.342px;
  cy: 34.439px;
  r: 4.658px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.h2k9w8b3k {
  cx: 24px;
  cy: 26.158px;
  r: 8.28px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.lzfx1bbox {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.108 18.85c.01-.082.01-.165.01-.248v-2.37h7.764v2.37c0 .083 0 .166.01.249m.766-9.254a5.177 5.177 0 0 1 5.175 5.176v3.83a2.97 2.97 0 0 1-2.94 2.98m-13.786 0a2.98 2.98 0 0 1-2.94-2.98v-3.83a5.177 5.177 0 0 1 5.175-5.176");
}

.ougufmpwh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.274 26.442c.067.05.139.091.21.133l2.053 1.185l-3.881 6.723l-2.053-1.185q-.106-.065-.22-.116m7.63 5.291a5.177 5.177 0 0 1-7.07 1.894l-3.316-1.915a2.97 2.97 0 0 1-1.112-4.036m6.894-11.94a2.98 2.98 0 0 1 4.051-1.055l3.317 1.914a5.177 5.177 0 0 1 1.894 7.07M21.244 29.9c.621.52 1.224.758 2.73.758h.26a2.523 2.523 0 0 0 2.522-2.523h0a2.523 2.523 0 0 0-2.523-2.523h-2.99v-3.954h5.513");
}

.ow552-bev {
  cx: 24px;
  cy: 9.597px;
  r: 4.658px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zpcsdlb2i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.617 33.183a2 2 0 0 0-.22.115l-2.053 1.185l-3.881-6.723l2.053-1.185c.071-.042.143-.083.21-.133m-8.397 3.963a5.177 5.177 0 0 1 1.894-7.07l3.317-1.915a2.97 2.97 0 0 1 4.051 1.056m6.894 11.94a2.98 2.98 0 0 1-1.112 4.036l-3.317 1.915a5.177 5.177 0 0 1-7.07-1.894");
}

</style>
