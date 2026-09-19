<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="iord_t2rf"/><path class="swcsxqbov"/><circle class="vqogbbbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:soundaura" /></template>
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

.iord_t2rf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.41 27.5C10.99 34.09 16.93 39 24 39s13.01-4.91 14.59-11.5m-29.18-7C10.99 13.91 16.93 9 24 9s13.01 4.91 14.59 11.5");
}

.swcsxqbov {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22 32.26c-3.73-.9-6.5-4.26-6.5-8.26s2.77-7.36 6.5-8.26m4 0c3.73.9 6.5 4.26 6.5 8.26s-2.77 7.36-6.5 8.26");
}

.vqogbbbht {
  cx: 24px;
  cy: 24px;
  r: 0.75px;
  fill: currentColor;
}

</style>
