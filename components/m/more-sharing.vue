<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="kordmsl_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:more-sharing" /></template>
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

.kordmsl_q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.244 11.876h25.751M4.456 32.961h21.621m-23.49-7.028h35.326m-34.8-7.028H20.16m-7.028 7.028l7.028-7.028l-7.028-7.028m14.178 4.685l4.686-4.685L27.31 7.19m-5.918 30.456l4.686-4.685l-7.029-7.029m14.178 4.686l4.686-4.685l-4.686-4.686");
}

</style>
