<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="wwsq09bjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:songkick" /></template>
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

.wwsq09bjg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.657 24.047c4.983 1.308 9.23 3.159 9.23 7.028c0 3.505-2.901 6.056-7.527 6.056c-10.388 0-8.201-11.397-16.696-11.397c-3.491 0-5.762 2.425-5.762 2.425m20.755-4.112c-4.984-1.309-6.554-2.757-6.554-6.626c0-3.506 2.27-5.72 6.897-5.72c7.122 0 8.888 7.016 14.65 7.016c3.49 0 5.346-2.633 5.346-2.633");
}

</style>
