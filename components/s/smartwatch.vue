<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="scfsvuyqo"/><path class="rxfphkb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:smartwatch" /></template>
<style>
.rxfphkb7t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.856 28.523L23.831 24v-9.384m7.789-1.971l-.931-6.432a2 2 0 0 0-1.98-1.713h-9.757a2 2 0 0 0-1.979 1.713l-.931 6.432m0 22.71l.931 6.432a2 2 0 0 0 1.98 1.713h9.757a2 2 0 0 0 1.979-1.713l.931-6.432");
}

.scfsvuyqo {
  cx: 23.831px;
  cy: 24px;
  r: 13.771px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
