<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lcgmgrd6n"/><path class="og-53mbsn"/><circle class="i6gq-ob6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:opensuse-leap-micro" /></template>
<style>
.i6gq-ob6h {
  cx: 24px;
  cy: 20.5px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.lcgmgrd6n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 8.5l12 12l-12 12l-12-12z");
}

.og-53mbsn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36 27.5l-12 12l-12-12m24-7h6.5m-37 0H12");
}

</style>
