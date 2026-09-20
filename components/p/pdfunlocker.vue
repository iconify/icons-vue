<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xzxvf6vto"/><path class="q8gbagjif"/><path class="kpvesj0hq"/><circle class="jakxx0b3v"/><path class="hoqf82bmh"/><rect class="ion6lkb5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pdfunlocker" /></template>
<style>
.hoqf82bmh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.547 31.769v2.753");
}

.ion6lkb5v {
  width: 19.291px;
  height: 12.637px;
  x: 14.901px;
  y: 24.823px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.419px;
  ry: 1.419px;
}

.jakxx0b3v {
  cx: 24.547px;
  cy: 30.004px;
  r: 1.766px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.kpvesj0hq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.353 22.031v-7.333h-8.334a1.853 1.853 0 0 1-1.852-1.854V4.5H11.5c-1.023 0-1.852.83-1.852 1.854v15.678m-.001 0v19.33c0 1.181.83 2.138 1.852 2.138h25.002c1.023 0 1.852-.957 1.852-2.137v-19.33");
}

.q8gbagjif {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.163 24.823V22.55c.02-2.994 2.89-5.409 6.413-5.393c3.496.016 6.325 2.422 6.344 5.393v2.273M28.167 4.5l10.186 10.198");
}

.xzxvf6vto {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.163 24.823V22.55c.02-2.994 2.89-5.409 6.413-5.393c3.496.016 6.325 2.422 6.344 5.393v2.273");
}

</style>
