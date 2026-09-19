<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="z5y2ycbwj"/><path class="i__xczbpm"/></g><path class="eajlt_zah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:starlight-launcher" /></template>
<style>
.eajlt_zah {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.748 5.384a21.5 21.5 0 0 1 5.784 4.867m-27.28 32.365C2.97 36.68-.552 23.533 5.384 13.252a21.4 21.4 0 0 1 6.649-7.115c4.432-3.127 6.567-.312 7.458 1.522s.384 5.743-1.488 7.58c-1.12 1.098-1.727 1.311-3.198 3.452a10.62 10.62 0 0 0 .381 11.233");
}

.i__xczbpm {
  d: path("M11.564 36.317a4.612 4.612 0 0 0 7.987 4.611l16.885-29.245m-7.987-4.611a4.612 4.612 0 0 1 7.987 4.611m-7.987-4.611L11.564 36.317");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z5y2ycbwj {
  d: path("M13.252 42.616a21.5 21.5 0 0 1-5.784-4.867m27.28-32.365c10.282 5.936 13.805 19.083 7.868 29.364a21.4 21.4 0 0 1-6.649 7.115c-4.432 3.128-6.567.312-7.458-1.522s-.384-5.743 1.488-7.58c1.12-1.098 1.727-1.311 3.198-3.452a10.62 10.62 0 0 0-.381-11.233");
}

</style>
