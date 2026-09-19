<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="gwbaepbmb"/><path class="jzi9xybht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:meipian-photo-album-maker" /></template>
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

.gwbaepbmb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.821 17.68l9.285 17.132L33.39 17.68Z");
}

.jzi9xybht {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.821 17.68c-11.762 8.299-1.559 23.182 9.285 17.132c10.508 5.697 20.723-7.464 9.284-17.133c-.778-12.865-19.541-10.317-18.569 0");
}

</style>
