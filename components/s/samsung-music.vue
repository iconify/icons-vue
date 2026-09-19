<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="e_81gsb2o"/><path class="zme12fbrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:samsung-music" /></template>
<style>
.e_81gsb2o {
  cx: 15.16px;
  cy: 35.481px;
  r: 8.399px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zme12fbrs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.559 35.481V4.88h4.358a13.32 13.32 0 0 1 13.321 13.322h0v5.542");
}

</style>
