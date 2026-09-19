<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yxwk8_bsw"/><circle class="u75-exb7z"/><path class="t0a9tpqtj"/><path class="c8qk3govv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:slmc" /></template>
<style>
.c8qk3govv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M3.5 24.089L13.928 6.173h20.233L44.5 24.09L34.16 41.826H13.84zM14.017 6.182l3.869 8.138m11.141 2.63l5.16-10.786");
}

.t0a9tpqtj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.474 16.602v4.322h5.446v-4.358z");
}

.u75-exb7z {
  cx: 29.704px;
  cy: 20.167px;
  r: 1.702px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yxwk8_bsw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.05 31.754h-9.804V16.067c.032-.666.855-1.64 1.675-1.622h6.31c.73-.003 1.757.747 1.792 1.497zm0-8.022h1.39c.709-.02.67.16.67.9l.089 4.858c.03 1.89 3.226 1.89 3.244 0l-.089-10.072l-3.636-3.636");
}

</style>
