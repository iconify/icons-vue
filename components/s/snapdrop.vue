<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ez1hqvbxn"/><path class="pnj3pul2e"/><path class="yyul_hbvi"/><circle class="p76ate-mk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:snapdrop" /></template>
<style>
.ez1hqvbxn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.77 42.915a21.5 21.5 0 1 1 20.408.028");
}

.p76ate-mk {
  cx: 24px;
  cy: 24px;
  r: 4.739px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pnj3pul2e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  d: path("M31.506 38.227a16.125 16.125 0 1 0-15.012 0");
}

.yyul_hbvi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.826 33.582a10.75 10.75 0 1 0-9.652 0");
}

</style>
