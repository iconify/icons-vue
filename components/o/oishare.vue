<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="vd0tlfi9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:oishare" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.vd0tlfi9f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.039 35.13a4.58 4.58 0 0 0-4.128-4.15l-.012.012m.736 3.387a1.836 1.836 0 1 0 0 2.597a1.836 1.836 0 0 0 0-2.597m7.624.481a9.006 9.006 0 0 0-8.105-8.105m15.141-16.269L19.3 19.482a1 1 0 0 0 0 1.414l6.704 6.704m1.793 8.557l8.996-8.996a1 1 0 0 0 0-1.414l-6.704-6.704");
}

</style>
