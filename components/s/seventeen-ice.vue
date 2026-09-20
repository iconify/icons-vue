<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xssa_c4_l"/><circle class="mqstn8btj"/><path class="mt1lryazy"/><circle class="ev6bl5b3f"/><circle class="dla93abyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:seventeen-ice" /></template>
<style>
.dla93abyv {
  cx: 15.331px;
  cy: 18.471px;
  r: 0.75px;
  fill: currentColor;
}

.ev6bl5b3f {
  cx: 12.334px;
  cy: 18.612px;
  r: 0.75px;
  fill: currentColor;
}

.mqstn8btj {
  cx: 13.832px;
  cy: 20.293px;
  r: 0.75px;
  fill: currentColor;
}

.mt1lryazy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.659 15.584l-.063-1.556L5.5 13.5V7l11.635.5l.414 7.764zm5.467 5.887a1.75 1.75 0 0 1-1.212.57a1.75 1.75 0 0 1-1.26-.454");
}

.xssa_c4_l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.12 12.964l2-7.464L41.914 10L34 42.5l-7.566-2.028l5.563-26.009zM18.068 25L19 42.5L10.69 41l-.636-15.675z");
}

</style>
