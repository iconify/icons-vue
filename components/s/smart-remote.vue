<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="f105wsb8b"/><path class="fru03_b9e"/><rect class="wzvfagbai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:smart-remote" /></template>
<style>
.f105wsb8b {
  cx: 24.119px;
  cy: 28.818px;
  r: 2.72px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.fru03_b9e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.34 8.953c2.125-2.759 5.74-4.43 9.625-4.453c3.886-.022 7.527 1.61 9.694 4.344M19.6 12.978c.962-1.25 2.6-2.007 4.36-2.017s3.408.73 4.39 1.968");
}

.wzvfagbai {
  width: 12.48px;
  height: 25.477px;
  x: 17.808px;
  y: 18.023px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.361px;
  ry: 2.361px;
}

</style>
