<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cdpqd_bya"/><path class="cl7062ymn"/><path class="s9gk1jqim"/><path class="prgvtl7pl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:reolink" /></template>
<style>
.cdpqd_bya {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.364 24.079v7.4h7.4");
}

.cl7062ymn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.364 24.079a7.4 7.4 0 0 1 7.4-7.4h0a7.4 7.4 0 0 1 7.4 7.4h0a7.4 7.4 0 0 1-7.4 7.4h0");
}

.prgvtl7pl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 24v18.5H24");
}

.s9gk1jqim {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 24A18.5 18.5 0 0 1 24 5.5h0A18.5 18.5 0 0 1 42.5 24h0A18.5 18.5 0 0 1 24 42.5h0");
}

</style>
