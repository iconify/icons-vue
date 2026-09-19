<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="focdz6ehl"/><path class="m981hbcvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:streamplayer" /></template>
<style>
.focdz6ehl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.28 21.703V9.046c0-1.477 1.564-2.418 2.877-1.729l23.181 12.252m4.114 2.167l1.006.535c1.39.733 1.39 2.724 0 3.457L13.157 40.683c-1.313.69-2.877-.252-2.877-1.729v-10.6");
}

.m981hbcvi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.526 32.92c-.368-7.476 3.182-13.109 12.506-13.173c5.555-.038 5.03 2.392 11.656 2.392s8.71-4.048 9.017-10.673l2.883 3.067c1.043 10.428-7.736 13.85-12.636 13.557c-5.13-.307-5.138-2.124-10.749-2.513c-4.913-.34-9.488.897-9.986 9.997z");
}

</style>
