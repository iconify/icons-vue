<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="h63gjzb-b"/><circle class="ei5s5wnmf"/><path class="ihvqhub0d"/><path class="ivkrauxkk"/><path class="cwsr-abbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zoho-workplace" /></template>
<style>
.cwsr-abbh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.517 31.167L16.552 28.3v-8.6l7.447-4.3l7.448 4.3v8.6L24 32.6");
}

.ei5s5wnmf {
  cx: 24px;
  cy: 13.25px;
  r: 2.15px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.h63gjzb-b {
  cx: 14.69px;
  cy: 29.375px;
  r: 2.15px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ihvqhub0d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 2.5l18.62 10.75v21.5L24 45.5L5.38 34.75v-21.5z");
}

.ivkrauxkk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.379 13.252L24 24l18.621-10.748M24 24v21.5");
}

</style>
