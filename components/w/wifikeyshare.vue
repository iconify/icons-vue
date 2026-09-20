<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rd79aqojs"/><circle class="tt-hivb6e"/><path class="c_bf97btb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wifikeyshare" /></template>
<style>
.c_bf97btb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.09 41.91v-6.43H19.77m11.1 3.71v-3.71");
}

.rd79aqojs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.8 5.5a30 30 0 0 1 29.41 24.19M12.8 13.16a22.32 22.32 0 0 1 21.54 16.53M12.8 20.81a14.67 14.67 0 0 1 13.48 8.88");
}

.tt-hivb6e {
  cx: 13.34px;
  cy: 35.48px;
  r: 6.43px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
