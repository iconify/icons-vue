<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h7nrtjboc"/><path class="agmh66bwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nespresso" /></template>
<style>
.agmh66bwb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.663 15.847V32.54c-3.64-5.593-8.485-12.276-14.2-18.064c-2.713-2.747-6.072-4.07-9.037-4.07a13.6 13.6 0 0 0-3.857.573");
}

.h7nrtjboc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.476 32.153V15.46c3.64 5.593 8.485 12.276 14.2 18.064c2.713 2.747 6.072 4.07 9.036 4.07a13.6 13.6 0 0 0 3.857-.572");
}

</style>
