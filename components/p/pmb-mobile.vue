<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="u9sy-pe9p"/><path class="dysp_fezq"/><path class="uq688bbah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pmb-mobile" /></template>
<style>
.dysp_fezq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.202 19.149l5.602 3.234v12.936L29.6 41.787l-5.602-3.234l11.204-6.47l-5.601-3.234m-16.805-9.701V12.68L24 6.213l11.203 6.468v6.468l-11.205-6.468v6.468");
}

.u9sy-pe9p {
  cx: 23.999px;
  cy: 25.617px;
  r: 6.468px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.uq688bbah {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 38.553l-5.601 3.232l-11.203-6.468V22.381l5.602-3.234v12.938l5.602-3.234");
}

</style>
