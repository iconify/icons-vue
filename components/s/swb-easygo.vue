<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="zoc85ebyi"/><path class="gt7otxbkb"/>`;
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

.gt7otxbkb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.728 31.04a3.11 3.11 0 0 0-3.108-3.109h0a3.11 3.11 0 0 0-3.108 3.108v3.166a3.11 3.11 0 0 0 3.108 3.108h0a3.11 3.11 0 0 0 3.108-3.108H19.62m8.76-6.274a3.1 3.1 0 0 1 3.108 3.108v3.166c0 1.722-1.386 3.108-3.108 3.108s-3.108-1.386-3.108-3.108V31.04a3.1 3.1 0 0 1 3.108-3.108M16.443 15.257a2.35 2.35 0 0 1-2.038 1.183h0a2.345 2.345 0 0 1-2.346-2.345V12.57a2.345 2.345 0 0 1 2.346-2.345h0a2.345 2.345 0 0 1 2.345 2.345v.762h-4.69m11.271 3.103v-6.216m0 3.87a2.345 2.345 0 0 1-2.345 2.346h0a2.345 2.345 0 0 1-2.346-2.346v-1.524a2.345 2.345 0 0 1 2.346-2.346h0a2.345 2.345 0 0 1 2.345 2.346m2.025 3.346c.428.36.89.524 1.929.524h.526c.856 0 1.55-.696 1.55-1.554h0c0-.858-.693-1.554-1.55-1.554H26.76c-.856 0-1.55-.696-1.55-1.554h0c0-.858.693-1.554 1.55-1.554h.526c1.038 0 1.5.165 1.929.525m6.726-.525v3.87a2.345 2.345 0 0 1-2.345 2.346h0a2.345 2.345 0 0 1-2.346-2.346v-3.87m4.691 3.87v3.167a2.345 2.345 0 0 1-2.345 2.345h0a2.34 2.34 0 0 1-1.659-.687");
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
