<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="y7i094tms"/><circle class="edi79mb8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:supertuxkart" /></template>
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

.edi79mb8h {
  cx: 24px;
  cy: 24px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.y7i094tms {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.947 19.96a4.54 4.54 0 0 1 2.1 2.092l10.702-2.81a15.53 15.53 0 0 0-9.99-9.99Zm-5.987 2.093a4.54 4.54 0 0 1 2.092-2.1L19.241 9.252a15.53 15.53 0 0 0-9.99 9.989Zm8.08 3.894a4.54 4.54 0 0 1-2.092 2.1l2.811 10.702a15.53 15.53 0 0 0 9.99-9.99Zm-5.988 2.1a4.54 4.54 0 0 1-2.092-2.1L9.251 28.759a15.53 15.53 0 0 0 9.989 9.99Z");
}

</style>
