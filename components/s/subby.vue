<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="ir0q2mbrv"/><path class="h5b-xo3li"/><path class="jez2e0h_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:subby" /></template>
<style>
.h5b-xo3li {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m39.5 21.352l-.581 3.298c-.195 1.103-1.248 1.998-2.352 1.998h0c-1.103 0-1.84-.895-1.646-1.998l.582-3.298M8.5 25.772c.378.639.95.876 1.806.876h1.183c1.102 0 2.152-.895 2.347-1.998h0c.195-1.104-.54-1.999-1.642-1.999h-1.308c-1.1 0-1.836-.895-1.641-1.999h0c.194-1.103 1.245-1.998 2.346-1.998h1.184c.855 0 1.428.238 1.806.876m5.533 5.12c-.195 1.103-1.247 1.998-2.351 1.998h0c-1.104 0-1.841-.895-1.646-1.998l.581-3.298");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.ir0q2mbrv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m38.919 24.65l-.476 2.698c-.195 1.104-1.247 1.998-2.351 1.998h0c-.552 0-1.012-.223-1.31-.585");
}

.jez2e0h_g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.561 26.648c-.441 0-.736-.358-.658-.8l.792-4.496m2.079 1.998c.195-1.103 1.247-1.998 2.351-1.998h0c1.104 0 1.841.895 1.646 1.998l-.229 1.3c-.194 1.103-1.247 1.998-2.35 1.998h0c-1.105 0-1.842-.895-1.647-1.999m-.352 1.999l1.409-7.994m5.499 4.696c.195-1.103 1.248-1.998 2.352-1.998h0c1.103 0 1.84.895 1.646 1.998l-.23 1.3c-.194 1.103-1.247 1.998-2.35 1.998h0c-1.104 0-1.841-.895-1.647-1.999m-.352 1.999l1.41-7.994");
}

</style>
