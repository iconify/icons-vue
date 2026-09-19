<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oybpqjj5m"/><path class="yr8a-hb7p"/><circle class="cv5-bjqvg"/><circle class="oer2qkwxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:talkie" /></template>
<style>
.cv5-bjqvg {
  cx: 21.395px;
  cy: 16.488px;
  r: 1.798px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.oer2qkwxk {
  cx: 29.418px;
  cy: 16.488px;
  r: 1.798px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.oybpqjj5m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.166 33.636l.05-11.09l-5.89-.026l.024-5.385L21.436 4.536l6.398-.036l.12 6.731l9.681-.027l.038 11.465l-9.81-.022l.167 6.782q.051.383.18.747c.134.375.33.729.579 1.04c.23.287.51.54.837.712c.403.213.862.295 1.316.337a8.7 8.7 0 0 0 2.512-.144a9.5 9.5 0 0 0 4.048-1.886");
}

.yr8a-hb7p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m37.502 30.235l.154 11.08a.42.42 0 0 1-.311.412l-1.752.468c-2.057.55-4.148.98-6.267 1.181c-1.344.128-2.704.196-4.041.007a10.7 10.7 0 0 1-6.352-3.35a10.7 10.7 0 0 1-2.765-6.626");
}

</style>
