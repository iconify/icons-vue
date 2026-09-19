<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="zpalb_bdg"/><path class="ik2f_tbql"/><circle class="xu79t9b8f"/><path class="q6hs0p5es"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wonderland" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.ik2f_tbql {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 24.972H32.023l-4.878-5.509l-4.879 5.509v9.43m11.187-7.012v2.95m3.806-3.076v3.021m3.302-2.306v3.13");
}

.q6hs0p5es {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.471 17.991l1.251-2.167H16.22l-1.25-2.166l-1.251 2.166h-2.502l1.251 2.167l-1.251 2.166h2.502l1.251 2.166l1.25-2.166h2.502zm12.744-9.572l.628 1.767l1.695-.805l-.806 1.694l1.768.628l-1.768.629l.806 1.694l-1.695-.805l-.628 1.767l-.628-1.767l-1.695.805l.806-1.694l-1.768-.629l1.768-.628l-.806-1.694l1.695.805zm-13.68 16.958l-3.004 5.204h6.009z");
}

.xu79t9b8f {
  cx: 27.082px;
  cy: 26.486px;
  r: 2.166px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zpalb_bdg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 35.36c12.981 4.08 23.2-5.215 29.972-5.215c2.252 0 4.727.74 7.028 1.727");
}

</style>
