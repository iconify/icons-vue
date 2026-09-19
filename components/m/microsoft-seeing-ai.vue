<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o203it5uq"/><path class="xmlqisb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:microsoft-seeing-ai" /></template>
<style>
.o203it5uq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 9.5c9.683 0 17.722 11.42 19.5 14.5c-1.778 3.08-9.817 14.5-19.5 14.5S6.278 27.08 4.5 24C6.278 20.92 14.317 9.5 24 9.5");
}

.xmlqisb5h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.872 34.596c-.539-1.117-.49-2.646.13-3.72A3.75 3.75 0 0 1 17.25 29h12.5c1.385 0 2.5-1.115 2.5-2.5s-1.115-2.5-2.5-2.5h-11.5c-1.385 0-2.5-1.115-2.5-2.5s1.115-2.5 2.5-2.5h12.5a3.75 3.75 0 0 0 3.248-1.875c.62-1.074.669-2.603.13-3.72");
}

</style>
