<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o7rw0ot1i"/><path class="cdun8qyge"/><path class="v9r4c5bup"/><path class="g4iy7n_ne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sl" /></template>
<style>
.cdun8qyge {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.79 20.29a15.79 15.79 0 0 1-31.58 0");
}

.g4iy7n_ne {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.41 23.26a2.22 2.22 0 0 0 1.85.83h1.12a1.86 1.86 0 0 0 1.86-1.85a1.86 1.86 0 0 0-1.86-1.86h-1.21a1.87 1.87 0 0 1-1.86-1.86a1.87 1.87 0 0 1 1.86-1.86h1.12a2 2 0 0 1 1.85.84m4.65-.93V24h3.71");
}

.o7rw0ot1i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 20.29a19.5 19.5 0 0 1-39 0");
}

.v9r4c5bup {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.07 20.29a12.07 12.07 0 0 1-24.14 0m24.14 0a12.07 12.07 0 1 0-24.14 0");
}

</style>
