<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bhif9p9ez"/><path class="yd0f94b1e"/><path class="qqe072blk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:privacy-space" /></template>
<style>
.bhif9p9ez {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.344 5.5h27.312a3.16 3.16 0 0 1 3.169 3.168v27.309a3.16 3.16 0 0 1-3.169 3.168H10.344a3.16 3.16 0 0 1-3.169-3.168V8.668A3.16 3.16 0 0 1 10.344 5.5");
}

.qqe072blk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 18.145a2.454 2.454 0 0 0-2.455 2.452a2.45 2.45 0 0 0 1.106 2.048v2.271c0 .878.602 1.585 1.349 1.585s1.35-.707 1.35-1.585v-2.27A2.454 2.454 0 0 0 24 18.145m-7.12 21.001v1.77a1.58 1.58 0 0 1-1.585 1.584h-.476a1.58 1.58 0 0 1-1.585-1.584v-1.77m21.532 0v1.77A1.58 1.58 0 0 1 33.18 42.5h-.476a1.58 1.58 0 0 1-1.584-1.584v-1.77");
}

.yd0f94b1e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.367 22.323c0 5.172-4.194 9.365-9.367 9.365a9.366 9.366 0 1 1 0-18.731c5.173 0 9.367 4.193 9.367 9.366");
}

</style>
