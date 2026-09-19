<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="p150l78mc"/><path class="wb5c54blz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:routematic" /></template>
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

.p150l78mc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.5 29.579V16.42h4.307c2.436 0 4.41 1.979 4.41 4.42s-1.974 4.418-4.41 4.418H11.5m4.307.001l4.307 4.316m3.229-5.424a3.29 3.29 0 0 1 3.29-3.29h0a3.29 3.29 0 0 1 3.289 3.29v5.427m-6.579-8.716v8.716");
}

.wb5c54blz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.922 24.151a3.29 3.29 0 0 1 3.289-3.29h0a3.29 3.29 0 0 1 3.29 3.29v5.427");
}

</style>
