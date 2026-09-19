<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j1v_u9btl"/><path class="lknrb06ha"/><rect class="epd9kstvr"/><path class="pavdgljme"/><circle class="q38mcdvtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:postnl" /></template>
<style>
.epd9kstvr {
  width: 3.877px;
  height: 5.138px;
  x: 15.358px;
  y: 21.997px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.939px;
}

.j1v_u9btl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.572 5.716c4.444 0 11.584 2.82 16.337 5.442c5.224 2.88 12.584 8.762 12.591 12.818c-.008 4.316-7.534 10.03-12.591 12.82c-4.592 2.53-11.584 5.488-16.175 5.488a6.1 6.1 0 0 1-2.953-.616C7.153 39.667 5.5 31.094 5.5 23.976A44.3 44.3 0 0 1 6.766 13.43c.967-3.76 2.356-6.229 4.015-7.145a5.8 5.8 0 0 1 2.791-.57m1.18 14.43h5.108m-2.554-1.359v-2.935");
}

.lknrb06ha {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.947 17.025c-.367-1.115-1.032-.979-1.436-.585c-.297.29-.102 1.6.495 2.226m3.658-1.641c.367-1.115 1.033-.979 1.436-.585c.297.29.103 1.6-.495 2.226");
}

.pavdgljme {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.185 26.701a2.18 2.18 0 0 0 1.595.434h.435a1.283 1.283 0 0 0 1.281-1.285h0a1.283 1.283 0 0 0-1.281-1.284h-.87a1.283 1.283 0 0 1-1.282-1.285h0a1.283 1.283 0 0 1 1.282-1.284h.435a2.18 2.18 0 0 1 1.595.433m2.887-2.032v5.767a.97.97 0 0 0 .97.97h.29m-2.278-5.138h2.036m6.024 5.138v-3.2a1.94 1.94 0 0 0-1.939-1.938h0a1.94 1.94 0 0 0-1.939 1.939v3.199m0-3.199v-1.939M9.6 25.168a1.94 1.94 0 0 0 1.939 1.939h0a1.94 1.94 0 0 0 1.939-1.94v-1.26a1.94 1.94 0 0 0-1.94-1.938h0A1.94 1.94 0 0 0 9.6 23.908m0-1.939v7.755M36.182 19.38v7.755");
}

.q38mcdvtx {
  cx: 17.306px;
  cy: 13.972px;
  r: 0.75px;
  fill: currentColor;
}

</style>
