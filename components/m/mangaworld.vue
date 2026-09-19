<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="t4aa_jbwr"/><path class="t1l42sncy"/><ellipse class="op4siccem"/><path class="fpr6xrl_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mangaworld" /></template>
<style>
.fpr6xrl_h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.588 17.445c-1.377 2.01-4.801.92-7.192 2.01m8.872-.269c-2.276 1.39-6.274.866-7.97 2.068M41.16 6.96L25.169 27.162M43.5 14.175L19.905 37.848");
}

.op4siccem {
  cx: 14.854px;
  cy: 19.604px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.465px;
  ry: 2.73px;
}

.t1l42sncy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.502 19.356V36.1c1.24 5.274 16.499 7.705 20.667.193V19.374");
}

.t4aa_jbwr {
  cx: 14.835px;
  cy: 19.459px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 10.335px;
  ry: 5.051px;
}

</style>
