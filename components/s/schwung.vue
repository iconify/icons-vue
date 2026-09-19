<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="zgyhqxv5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:schwung" /></template>
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

.zgyhqxv5c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.77 20.6c2.34-1.25 10.46-5.22 19.88-5.45c6.7-.16 11.08-.73 16.79-6.09M9.32 39.69c4.88-3.93 9.02-4.39 15-4.54c10.64-.26 19.62-5.28 20.5-5.79");
}

</style>
