<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g2wj9jbhp"/><path class="grz9shlzu"/><path class="u-s9vmbsn"/><path class="kf2dq0atz"/><path class="zlj9pptjp"/><path class="rwsv9hbep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:match-land" /></template>
<style>
.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.grz9shlzu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.167 23.879c1.55 0 2.983 1.156 3.758 3.032s.774 4.187 0 6.063c-.776 1.876-2.208 3.032-3.758 3.032m35.589-12.552c-1.55 0-2.982 1.156-3.757 3.032s-.775 4.187 0 6.063s2.207 3.032 3.757 3.032M18.827 15.7c-.601 2.624-2.26 4.751-3.705 4.751s-2.13-2.127-1.528-4.752s2.26-4.752 3.705-4.752s2.13 2.128 1.528 4.752m10.099.007c.601 2.624 2.26 4.752 3.705 4.752s2.13-2.127 1.528-4.752s-2.26-4.752-3.705-4.752s-2.13 2.127-1.528 4.752");
}

.kf2dq0atz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.917 24.12l5.173 3.429l3.97-3.128l4.09 3.007l4.932-3.248");
}

.rwsv9hbep {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.226 32.301c3.008-.481 9.624.842 10.707 1.564");
}

.u-s9vmbsn {
  fill: currentColor;
  d: path("M17.953 13.323a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m13.537 0a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.zlj9pptjp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.323 25.935c0 16 13.339 15.256 13.219.098");
}

</style>
