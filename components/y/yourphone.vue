<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f2fl1cc_c"/><path class="eke5iebnr"/><circle class="iaxkgf5ko"/><path class="bubl3jbyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yourphone" /></template>
<style>
.bubl3jbyf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.77 31.51h5.06m29.4.01H29.32M18.96 14.6h6.26");
}

.eke5iebnr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.6 11.2a1.77 1.77 0 0 0-1.77 1.8v26.56a1.67 1.67 0 0 0 1.67 1.67h14.18a1.66 1.66 0 0 0 1.64-1.65V12.89a1.67 1.67 0 0 0-1.67-1.67Z");
}

.f2fl1cc_c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.32 34H41.8c.94 0 1.7-.56 1.7-1.25v-1.23h-2.27v-23a1.69 1.69 0 0 0-1.69-1.69H8.47a1.69 1.69 0 0 0-1.7 1.68v23H4.5v1.25c0 .69.75 1.25 1.7 1.25h5.63");
}

.iaxkgf5ko {
  cx: 16.83px;
  cy: 14.6px;
  r: 0.73px;
  fill: currentColor;
}

</style>
