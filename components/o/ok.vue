<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="lf8u20vph"/><path class="qco4uuxrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ok" /></template>
<style>
.lf8u20vph {
  cx: 23.997px;
  cy: 13.762px;
  r: 8.034px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qco4uuxrv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.219 26.897a17.53 17.53 0 0 0 11.778 4.514c4.53 0 8.679-1.7 11.794-4.514M16.792 44.729l5.764-13.311m8.645 13.311l-5.788-13.368");
}

</style>
