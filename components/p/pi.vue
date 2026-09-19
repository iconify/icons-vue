<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="my9h5m-xw"/><ellipse class="bzjtnwhjm"/><ellipse class="ehja5-_zh"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pi" /></template>
<style>
.bzjtnwhjm {
  cx: 19.782px;
  cy: 13.461px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.541px;
  ry: 1.5px;
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ehja5-_zh {
  cx: 28.217px;
  cy: 13.461px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.541px;
  ry: 1.5px;
}

.my9h5m-xw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.5 14.824v1.426a2.775 2.775 0 0 1-2.811 2.737H15.311a2.775 2.775 0 0 0-2.812 2.737v1.427m15.718-4.163v16.577m-8.435-16.577v16.577");
}

</style>
