<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kek12ubyn"/><circle class="v6exhlbqt"/><path class="h80iudbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:universal-tuner" /></template>
<style>
.h80iudbcb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.117 11.115a9.93 9.93 0 0 0-.593 13.693m14.952 0a9.93 9.93 0 0 0-.593-13.693M12.51 6.721a16.293 16.293 0 0 0-.592 22.481m24.164 0a16.29 16.29 0 0 0-.562-22.45");
}

.kek12ubyn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.202 4.5v23.156A3.2 3.2 0 0 1 24 30.858h0a3.2 3.2 0 0 1-3.202-3.202V4.5M24 30.858v9.296");
}

.v6exhlbqt {
  cx: 24px;
  cy: 41.827px;
  r: 1.673px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
