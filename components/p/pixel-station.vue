<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mot3btyoj"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pixel-station" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.mot3btyoj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.5 31.961V16.04h5.213c2.947 0 5.336 2.394 5.336 5.347s-2.39 5.348-5.336 5.348H11.5m14.767 3.482c.976 1.27 2.2 1.744 3.904 1.744h2.357A3.97 3.97 0 0 0 36.5 27.99v-.017A3.97 3.97 0 0 0 32.528 24h-2.6a3.976 3.976 0 0 1-3.976-3.976a3.985 3.985 0 0 1 3.984-3.985h2.345c1.703 0 2.927.473 3.904 1.744");
}

</style>
