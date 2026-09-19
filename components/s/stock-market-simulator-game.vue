<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="lm41q5boo"/><path class="kdy3eobdc"/><circle class="pr04tfb0n"/><circle class="ycc1et9yi"/><circle class="usn9ql8uz"/><circle class="o6dib7b5j"/><path class="zb32png8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:stock-market-simulator-game" /></template>
<style>
.kdy3eobdc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.606 14.375v6m3-3h-6");
}

.lm41q5boo {
  cx: 24.353px;
  cy: 23.121px;
  r: 15px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.o6dib7b5j {
  cx: 31.578px;
  cy: 31.544px;
  r: 0.75px;
  fill: currentColor;
}

.pr04tfb0n {
  cx: 29.279px;
  cy: 29.245px;
  r: 0.75px;
  fill: currentColor;
}

.usn9ql8uz {
  cx: 31.578px;
  cy: 26.947px;
  r: 0.75px;
  fill: currentColor;
}

.ycc1et9yi {
  cx: 33.876px;
  cy: 29.245px;
  r: 0.75px;
  fill: currentColor;
}

.zb32png8o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.995 10.739V5.5h-5.238m5.238 0l-27.99 27.991m0 3.77V42.5h5.238m-5.238 0l27.99-27.991");
}

</style>
