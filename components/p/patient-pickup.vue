<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1-cnxr8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:patient-pickup" /></template>
<style>
.x1-cnxr8h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 8.5h15l-1 13h-13Zm8 0v-3H17v3m-3.5-6H16A1.5 1.5 0 0 1 17.5 4A1.5 1.5 0 0 1 16 5.5h-2.5A1.5 1.5 0 0 1 12 4a1.5 1.5 0 0 1 1.5-1.5m-8.75 9h14.5m-7.25 3v4m-2-2h4");
}

</style>
