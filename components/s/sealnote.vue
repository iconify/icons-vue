<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t50hous9z"/><path class="ekj1_8t-q"/><g class="y9tr6bcfx"><circle class="v_pghqbwm"/><path class="vqxn8p5km"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sealnote" /></template>
<style>
.ekj1_8t-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.365 43.5v-8.667H8.524");
}

.t50hous9z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.524 4.5h30.952v39h-23.11l-7.842-8.64z");
}

.v_pghqbwm {
  cx: 24px;
  cy: 16.387px;
  r: 1.912px;
}

.vqxn8p5km {
  d: path("M26.823 22.688a5.624 5.624 0 0 0 2.458-6.557a5.546 5.546 0 0 0-5.9-3.778a5.55 5.55 0 0 0-1.117 10.79m4.559-.455l.002 10.938l-1.768 1.97L22.83 33.6l1.12-1.762l-2.242-2.275l1.619-2.17l-1.975-1.838l.915-2.342");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
