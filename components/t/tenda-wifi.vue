<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f3-5330to"/><path class="qxxpohbeu"/><path class="t9uo4nbdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tenda-wifi" /></template>
<style>
.f3-5330to {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 31.4s1.91 6.254 4.472 7.73h-8.945C22.713 35.95 24 31.4 24 31.4M4.5 20.135A22.51 22.51 0 0 1 24 8.87a22.51 22.51 0 0 1 19.5 11.265");
}

.qxxpohbeu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.849 23.803a15.18 15.18 0 0 1 13.15-7.597a15.18 15.18 0 0 1 13.152 7.597");
}

.t9uo4nbdk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.198 27.47a7.854 7.854 0 0 1 13.604 0");
}

</style>
