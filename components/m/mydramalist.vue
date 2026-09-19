<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="n73306ska"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mydramalist" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.n73306ska {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 29.591V18.396l5.604 11.208l5.604-11.191v11.191m2.382 0V18.396h2.521a4.903 4.903 0 0 1 4.903 4.904v1.4a4.903 4.903 0 0 1-4.903 4.904zm9.806-11.208v11.208H38.5");
}

</style>
