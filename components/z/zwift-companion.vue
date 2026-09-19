<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="og204ab9c"/><path class="qrbgzsw_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zwift-companion" /></template>
<style>
.og204ab9c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 20.5c0-7.5 6.1-13.6 13.6-13.6h.6");
}

.qrbgzsw_a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.8 20.5c0-5.1 4.1-9.2 9.2-9.2h.7m-.2 4.8c-2.2 0-4 1.8-4 4s1.8 4 4 4h3.1l-6.5 11.2c-1.1 1.9-.5 4.3 1.4 5.4c.6.4 1.3.5 2 .5h16.4c2.2 0 4-1.8 4-4s-1.8-4-4-4h-3.4l10-17.1z");
}

</style>
