<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="hzpefqbow"/><circle class="sn7lstb1z"/><circle class="f3go2_bgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:meeye-icon-pack" /></template>
<style>
.f3go2_bgd {
  cx: 27.491px;
  cy: 30.313px;
  r: 1.514px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hzpefqbow {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.065 42.5l.302-14.1c.02-.937.71-1.725 1.636-1.87l14.71-2.299a1.935 1.935 0 0 1 2.074 1.142l4.998 11.524a1.935 1.935 0 0 1-1.072 2.572l-1.537.6a3.9 3.9 0 0 0-2.159 2.08l-.153.351");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.sn7lstb1z {
  cx: 22.78px;
  cy: 31.07px;
  r: 1.514px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
