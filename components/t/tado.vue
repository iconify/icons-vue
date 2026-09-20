<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="ab8efm35s"/><circle class="gi1cy2bkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tado" /></template>
<style>
.ab8efm35s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.272 20.113v7.84c0 .728.59 1.317 1.317 1.317h.395m-3.096-6.983h2.767m7.659 4.348a2.635 2.635 0 1 1-5.27 0v-1.713a2.635 2.635 0 1 1 5.27 0m0 4.348v-6.983m7.329 2.635a2.635 2.635 0 1 0-5.27 0v1.713a2.635 2.635 0 1 0 5.27 0m0 2.635V18.73m4.694 3.557za2.635 2.635 0 0 1 2.635 2.635v1.713a2.635 2.635 0 1 1-5.27 0v-1.713a2.635 2.635 0 0 1 2.635-2.635");
}

.gi1cy2bkq {
  cx: 36.926px;
  cy: 20.838px;
  r: 1.186px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

</style>
