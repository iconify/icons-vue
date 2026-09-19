<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="ti1j71bpp"/><path class="oen6ze5rq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:super-simple-sleep-timer" /></template>
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

.oen6ze5rq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 10.563V24h7.344");
}

.ti1j71bpp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.569 13.65h5.3l-5.3 8h5.3m-11.884.995h4.13l-4.13 6.235h4.13m-9.353 1.374h3.001l-3.001 4.529h3.001M24 2.5v3.906M24 45.5v-4.219M45.5 24h-4.281M2.5 24h4.094");
}

</style>
