<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="o9eugbb_i"/><path class="id65_fbwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pacific-crest" /></template>
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

.id65_fbwo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.637 22.636l1.364-13.635l1.364 13.641m-.007 2.727l-1.418 13.63l-1.309-13.635M11 20.8V11h3.146c1.778 0 3.22 1.474 3.22 3.291c0 1.818-1.442 3.291-3.22 3.291H11m26-.068v.04c0 1.793-1.425 3.246-3.183 3.246s-3.183-1.453-3.183-3.246v-3.307c0-1.793 1.425-3.247 3.183-3.247S37 12.454 37 14.247v.04M17.366 33.714v.04c0 1.793-1.425 3.246-3.183 3.246S11 35.547 11 33.754v-3.307c0-1.793 1.425-3.247 3.183-3.247s3.183 1.454 3.183 3.247v.04M30.634 27.2v6.554c0 1.793 1.425 3.246 3.183 3.246S37 35.547 37 33.754V27.2");
}

.o9eugbb_i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9 24l15-1.5l14.997 1.56L24 25.5z");
}

</style>
