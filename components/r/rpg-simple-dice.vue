<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wkatvcbtz"/><path class="x00pz2oks"/><path class="owbl_-b3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rpg-simple-dice" /></template>
<style>
.owbl_-b3y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.31 32.45H11.69L24 10.59zM24 10.59V2.5m12.31 29.95l6.34 2.3m-30.96-2.3l-6.34 2.3");
}

.wkatvcbtz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.65 34.75v-21.5L24 2.5L5.35 13.25v21.5L24 45.5z");
}

.x00pz2oks {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.31 32.45l6.34-19.2L24 10.59L5.35 13.25l6.34 19.2L24 45.5z");
}

</style>
