<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="im_5f7tha"/><path class="tfnf72bky"/><circle class="b0qe_924h"/><path class="y-7i7bccf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:micasa-3d" /></template>
<style>
.b0qe_924h {
  cx: 33.234px;
  cy: 18.484px;
  r: 3.896px;
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.im_5f7tha {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.87 26.12a4.419 4.419 0 1 1 8.838 0v7.292m-8.839-11.71v11.71");
}

.tfnf72bky {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.707 26.12a4.419 4.419 0 1 1 8.838 0v7.292");
}

.y-7i7bccf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.234 26.247v7.165");
}

</style>
