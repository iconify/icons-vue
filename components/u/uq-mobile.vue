<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uo47pyvli"/><path class="p1ir-y5hh"/><path class="ebdch9m-m"/><circle class="wtofxac3x"/><path class="mm90x7b0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:uq-mobile" /></template>
<style>
.ebdch9m-m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.036 12.702v9.091c0 2.487 1.987 4.504 4.437 4.504s4.437-2.016 4.437-4.504v-9.091m8.62 0a4.44 4.44 0 0 1 4.437 4.447v4.7a4.44 4.44 0 0 1-4.437 4.447h0a4.44 4.44 0 0 1-4.438-4.447v-4.7a4.44 4.44 0 0 1 4.438-4.447m0 11.141l2.985 4.56M11.5 32.68c0-.878.71-1.588 1.587-1.588h0c.877 0 1.588.71 1.588 1.587v2.62M11.5 31.092v4.206m3.175-2.618c0-.878.71-1.588 1.587-1.588h0c.877 0 1.587.71 1.587 1.587v2.62");
}

.mm90x7b0d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.307 31.092v4.206m1.663-6.349v5.556c0 .438.355.793.793.793H32m4.292-.801a1.59 1.59 0 0 1-1.38.801h0c-.876 0-1.587-.71-1.587-1.587v-1.032c0-.876.711-1.587 1.588-1.587h0c.876 0 1.587.71 1.587 1.587v.516h-3.175m-8.833-.515c0-.878.711-1.588 1.588-1.588h0c.876 0 1.587.71 1.587 1.587v1.032c0 .876-.71 1.587-1.587 1.587h0c-.877 0-1.588-.71-1.588-1.587m0 1.587v-6.349m-4.876 3.731a1.587 1.587 0 0 1 3.175 0v1.03a1.587 1.587 0 0 1-3.175 0z");
}

.p1ir-y5hh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 27.64a66.6 66.6 0 0 1 29 0");
}

.uo47pyvli {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 42.5h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4");
}

.wtofxac3x {
  cx: 29.307px;
  cy: 29.147px;
  r: 0.75px;
  fill: currentColor;
}

</style>
