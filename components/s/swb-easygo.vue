<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="zoc85ebyi"/><path class="emhrr1bep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:swb-easygo" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.emhrr1bep {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.728 31.04a3.108 3.108 0 1 0-6.215 0v3.166a3.108 3.108 0 1 0 6.215 0H19.62m8.76-6.275a3.1 3.1 0 0 1 3.108 3.108v3.166c0 1.722-1.386 3.108-3.108 3.108s-3.108-1.386-3.108-3.108V31.04a3.1 3.1 0 0 1 3.108-3.108M16.443 15.257a2.345 2.345 0 0 1-4.383-1.162V12.57a2.345 2.345 0 1 1 4.691 0v.762H12.06m11.271 3.103v-6.216m0 3.87a2.345 2.345 0 1 1-4.691 0v-1.524a2.345 2.345 0 1 1 4.691 0m2.025 3.346c.428.36.89.524 1.929.524h.526c.856 0 1.55-.696 1.55-1.554s-.693-1.554-1.55-1.554H26.76c-.856 0-1.55-.696-1.55-1.554s.693-1.554 1.55-1.554h.526c1.038 0 1.5.165 1.929.525m6.726-.525v3.87a2.345 2.345 0 1 1-4.691 0v-3.87m4.691 3.87v3.167a2.345 2.345 0 0 1-2.345 2.345a2.34 2.34 0 0 1-1.659-.687");
}

.zoc85ebyi {
  cx: 24px;
  cy: 32.621px;
  r: 12.876px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
