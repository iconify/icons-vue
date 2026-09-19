<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zzs4as9xd"/><circle class="dzol507mk"/><circle class="beqsa12ge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:randomfilemaker" /></template>
<style>
.beqsa12ge {
  cx: 33.25px;
  cy: 14.75px;
  r: 9.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.dzol507mk {
  cx: 14.75px;
  cy: 33.25px;
  r: 9.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zzs4as9xd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.5H5.5V24H24ZM42.5 24H24v18.5h18.5Z");
}

</style>
