<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="ni-mndbrc"/><circle class="lo__bfb7q"/><path class="snwshob_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:traccarclient" /></template>
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

.lo__bfb7q {
  cx: 23.923px;
  cy: 24.077px;
  r: 1.193px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ni-mndbrc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.879 34.962a6.958 6.958 0 0 1-9.84-9.84l4.92 4.92Z");
}

.snwshob_g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.303 17.539a6.96 6.96 0 0 1 4.158 4.158M28.682 11A13.92 13.92 0 0 1 37 19.318");
}

</style>
