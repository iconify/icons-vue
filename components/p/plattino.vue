<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fxn2phfxe"/><path class="eoz7ydb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:plattino" /></template>
<style>
.eoz7ydb9d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.49 19.317c-1.509 8.016-3.008 16.023-1.98 19.56s4.595 2.595 7.161 2.374c2.566-.212 4.133.308 5.7.817M12.6 43.5a2.25 2.25 0 0 1 1.097-.394m3.469-1.096q.519-.327 1.548-.528");
}

.fxn2phfxe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.294 23.69c-3.633 5.037-11.188 5.796-16.878 1.702c-5.68-4.104-7.343-11.515-3.71-16.551c3.633-5.037 11.188-5.806 16.868-1.702c5.69 4.105 7.353 11.505 3.72 16.552");
}

</style>
