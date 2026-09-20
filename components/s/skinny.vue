<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="y5hey2b8m"/><path class="c1xw207df"/></g><path class="x9fcvusso"/><path class="kvvyqszdy"/><circle class="mejeafv4o"/><path class="sxqbf3hfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:skinny" /></template>
<style>
.c1xw207df {
  d: path("M14 14S4 14 4 25s10 10 10 10s0 5 10 5s10-5 10-5s9 0 9-10s-9-11-9-11s0-6-10-6s-10 6-10 6");
}

.kvvyqszdy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.996 22.045v3.3a2 2 0 1 1-4 0v-3.3");
}

.mejeafv4o {
  cx: 20.956px;
  cy: 19.688px;
  r: 0.75px;
  fill: currentColor;
}

.sxqbf3hfp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.956 22.138v5.3m12.015-.088v-3.3a2 2 0 1 0-4 0m0 3.299v-5.3");
}

.x9fcvusso {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27 27.391v-3.3a2 2 0 1 0-4 0m0 3.3v-5.3m15.996 3.254v2.7a2 2 0 0 1-2 2a2 2 0 0 1-1.415-.586");
}

.y5hey2b8m {
  d: path("M8.5 26.537c.49.639 1.105.876 1.961.876h1.184a1.996 1.996 0 0 0 1.996-1.995v-.01a1.996 1.996 0 0 0-1.996-1.995H10.34a2 2 0 0 1-1.998-1.998c0-1.106.896-2.002 2.002-2.002h1.178c.856 0 1.471.238 1.962.877m1.91-.812v8m.001-1.699l3.621-3.604m-2.468 2.457l2.846 2.834");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
