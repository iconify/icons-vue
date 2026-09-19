<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sj9_3-ozw"/><circle class="eff_hqbns"/><path class="edy6fe7nl"/><path class="dbtdijb3g"/><path class="kkxq43b-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pong" /></template>
<style>
.dbtdijb3g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.248 27.11a4.5 4.5 0 1 0 0-6.221");
}

.edy6fe7nl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.748 27.11a4.5 4.5 0 1 0 0-6.22");
}

.eff_hqbns {
  cx: 19.5px;
  cy: 24px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.kkxq43b-f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.747 27.11a4.5 4.5 0 1 0 .071-6.292");
}

.sj9_3-ozw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 8.5v31");
}

</style>
