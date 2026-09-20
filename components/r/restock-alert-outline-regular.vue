<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k70w93buq"/><path class="f4yp5uw0u"/><path class="jo_6okb9l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:restock-alert-outline-regular" /></template>
<style>
.f4yp5uw0u {
  d: path("M14 18.5a2 2 0 0 1 -4 0");
}

.jo_6okb9l {
  d: path("M9 8h6v6H9Z");
}

.k70w93buq {
  d: path("M6 15v-5a6 6 0 0 1 12 0v5l2.5 2.5h-17z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
