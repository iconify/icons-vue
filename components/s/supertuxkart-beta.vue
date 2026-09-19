<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f7smwvbai"/><path class="cnptktb2r"/><circle class="edi79mb8h"/><circle class="vi_nxfq0r"/><path class="funm8-8nd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:supertuxkart-beta" /></template>
<style>
.cnptktb2r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.947 19.96a4.54 4.54 0 0 1 2.1 2.092l10.702-2.81a15.53 15.53 0 0 0-9.99-9.99zm-5.987 2.093a4.54 4.54 0 0 1 2.092-2.1L19.241 9.252a15.53 15.53 0 0 0-9.99 9.989zm17.56 9.516a15.4 15.4 0 0 0 1.228-2.81l-10.707-2.812a4.54 4.54 0 0 1-2.093 2.1l2.811 10.702a15.5 15.5 0 0 0 2.81-1.228m-9.517-9.474a4.54 4.54 0 0 1-2.092-2.1L9.251 28.759a15.53 15.53 0 0 0 9.989 9.99z");
}

.edi79mb8h {
  cx: 24px;
  cy: 24px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.f7smwvbai {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.43 43.327A21.4 21.4 0 0 1 24 45.5C12.126 45.5 2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24a21.4 21.4 0 0 1-2.174 9.431");
}

.funm8-8nd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.536 38.5a2 2 0 1 1 0 4h-3.3v-8h3.3a2 2 0 1 1 0 4m0 0h-3.3");
}

.vi_nxfq0r {
  cx: 38.5px;
  cy: 38.5px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
