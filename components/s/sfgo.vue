<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="bjhlh6brs"/><path class="nm9i__dfi"/><path class="h_bhimouw"/><path class="dm5ij0bgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sfgo" /></template>
<style>
.bjhlh6brs {
  cx: 38.718px;
  cy: 24px;
  r: 5.782px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.dm5ij0bgv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.726 24.72c-.626 0-1.13-.494-1.13-1.107v-.719c0-.612.504-1.106 1.13-1.106s1.129.494 1.129 1.106v.72c0 .612-.504 1.105-1.13 1.105m3.985-2.931c.626 0 1.13.493 1.13 1.106v.719c0 .613-.504 1.106-1.13 1.106s-1.129-.493-1.129-1.106v-.719c0-.613.504-1.106 1.13-1.106");
}

.h_bhimouw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.218 29.782v-3.68c0-1.164.938-2.102 2.103-2.102h7.884m9.65-2.212v3.318c0 .61-.506 1.106-1.13 1.106a1.14 1.14 0 0 1-.798-.324");
}

.nm9i__dfi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.885 18.218H5.603A2.1 2.1 0 0 0 3.5 20.32v1.576C3.5 23.062 4.438 24 5.603 24h7.359c1.164 0 2.102.938 2.102 2.103v1.576a2.1 2.1 0 0 1-2.102 2.103H3.5");
}

</style>
