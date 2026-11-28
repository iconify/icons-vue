<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gs03h9bng"/><path clip-rule="evenodd" class="cu321hdir"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:serial-port-off" /></template>
<style>
.cu321hdir {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17 10C17 10.552 16.5523 11 16 11C15.4477 11 15 10.552 15 10C15 9.448 15.4477 9 16 9C16.5523 9 17 9.448 17 10Z");
  stroke: none;
}

.gs03h9bng {
  d: path("M17.9639 17.964C17.8118 17.988 17.6564 18 17.4987 18H6.5013C5.1247 18 3.9248 17.063 3.5909 15.728L2.0909 9.728C1.6175 7.834 3.0496 6 5.0013 6H6M11.6569 6H18.9987C20.9504 6 22.3825 7.834 21.9091 9.728L20.6042 14.947M2 2L22 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
