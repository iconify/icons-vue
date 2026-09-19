<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v3nr5b3-m"/><path class="ypz3rvb7i"/><circle class="c4r2858tq"/><path class="eh874mb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:maxim" /></template>
<style>
.c4r2858tq {
  cx: 29.851px;
  cy: 19.797px;
  r: 0.75px;
  fill: currentColor;
}

.eh874mb9u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.851 22.023v4.816m-9.491-4.816a2.41 2.41 0 0 1 2.408 2.408v2.408h-2.409a2.41 2.41 0 0 1-2.408-2.408h0a2.41 2.41 0 0 1 2.408-2.408");
}

.v3nr5b3-m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4M27.996 22.023l-3.635 4.816m3.635 0l-3.635-4.816");
}

.ypz3rvb7i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9 26.84v-3c0-1.003.814-1.817 1.818-1.817h0c1.003 0 1.817.814 1.817 1.818v2.998m0-2.999c0-1.003.814-1.817 1.818-1.817h0c1.003 0 1.817.814 1.817 1.818v2.998m15.46.001v-3c0-1.003.814-1.817 1.818-1.817h0c1.003 0 1.817.814 1.817 1.818v2.998m0-2.999c0-1.003.814-1.817 1.818-1.817h0c1.003 0 1.817.814 1.817 1.818v2.998");
}

</style>
