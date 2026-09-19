<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e4z0bdcnj"/><path class="uhq_6_bkt"/><path class="ue4a7t64e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:microsoftoutlook" /></template>
<style>
.e4z0bdcnj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.92 25.3v-4.77h0V7.5a2 2 0 0 0-2-2H15.55a2 2 0 0 0-2 2V14m4.64 8.19a3.68 3.68 0 0 0-3.89-3.68a3.83 3.83 0 0 0-3.49 3.89v3.41a3.69 3.69 0 0 0 3.69 3.69h0a3.69 3.69 0 0 0 3.69-3.69h0z");
}

.ue4a7t64e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.67 34v8.5H43.5V24.39l-15.91 9.17");
}

.uhq_6_bkt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 16v16a2 2 0 0 0 2 2h16a2 2 0 0 0 2-2V16a2 2 0 0 0-2-2h-16a2 2 0 0 0-2 2m39 26.5l-19-10.68");
}

</style>
