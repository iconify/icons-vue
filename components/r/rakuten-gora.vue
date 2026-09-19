<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vh2t5ob4s"/><path class="yp7nrgbhp"/><circle class="l40cd-dkp"/><path class="pjlghl6jh"/><circle class="kdfap6bnm"/><circle class="yiujgmbed"/><circle class="b4tesqbrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rakuten-gora" /></template>
<style>
.b4tesqbrf {
  cx: 15.55px;
  cy: 34.508px;
  r: 0.75px;
  fill: currentColor;
}

.kdfap6bnm {
  cx: 14.5px;
  cy: 32.583px;
  r: 0.75px;
  fill: currentColor;
}

.l40cd-dkp {
  cx: 13.75px;
  cy: 32.583px;
  r: 6px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pjlghl6jh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.75 20.5v12");
}

.vh2t5ob4s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.724 15.185V8.194h2.275c1.286 0 2.328 1.05 2.328 2.348s-1.042 2.348-2.328 2.348h-2.275M30 12.889l2.275 2.294m-5.419 1.444l6.288-.002l-5.072 1.182zm-7.108 15.956c.66-.055 1.33-.083 2.002-.083c6.075 0 11 2.238 11 5h0c0 2.761-4.925 5-11 5c-5.824 0-10.638-2.063-10.981-4.706m8.981-5.211V5.5");
}

.yiujgmbed {
  cx: 16.5px;
  cy: 32.583px;
  r: 0.75px;
  fill: currentColor;
}

.yp7nrgbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.75 5.5h20.5v15h-20.5z");
}

</style>
