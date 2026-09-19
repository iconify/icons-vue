<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="pwjztfbeq"/><rect class="hz_wrc9_e"/><path class="jwngsi8fh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vectras-vm" /></template>
<style>
.hz_wrc9_e {
  width: 21.423px;
  height: 21.423px;
  x: 13.288px;
  y: 13.288px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.441px;
  ry: 2.441px;
}

.jwngsi8fh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.07 16.688a2.377 2.377 0 0 0-2.383 2.382v3.715h6.098v-6.098zm6.145 0v6.097h6.098V19.07a2.377 2.377 0 0 0-2.383-2.382zm-8.527 8.527v3.715a2.377 2.377 0 0 0 2.382 2.382h3.715v-6.097zm8.527 0v6.098h3.715a2.377 2.377 0 0 0 2.382-2.383v-3.715zm16.053 16.053l-7.27-7.27M6.732 6.732l7.27 7.27");
}

.pwjztfbeq {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.216px;
  ry: 4.216px;
}

</style>
