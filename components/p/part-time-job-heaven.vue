<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="a24qwubmz"/><path class="xptd-zxyo"/><circle class="q7slq82ka"/><path class="g4s4ar7tg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:part-time-job-heaven" /></template>
<style>
.a24qwubmz {
  cx: 32.5px;
  cy: 15.5px;
  r: 10px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.g4s4ar7tg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 17.696A6 6 0 1 1 17.696 9.5c1.806 3.128 2.337 10.533 2.337 10.533s-7.405-.53-10.533-2.337");
}

.q7slq82ka {
  cx: 32.5px;
  cy: 15.5px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xptd-zxyo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.5 22.5a9.95 9.95 0 0 0-5.496 1.647l13.85 13.85A9.95 9.95 0 0 0 25.5 32.5c0-5.522-4.477-10-10-10m-8.353 4.504a9.94 9.94 0 0 0-1.553 4.16l11.242 11.242a9.94 9.94 0 0 0 4.16-1.553l-13.85-13.85zM5.5 36.785V42.5h5.715z");
}

</style>
