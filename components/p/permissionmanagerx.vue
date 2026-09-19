<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="of-55_bnc"/><path class="ca_q1pbmu"/><circle class="mek3mhbgb"/><path class="wymuw5w8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:permissionmanagerx" /></template>
<style>
.ca_q1pbmu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.41 28.498H43.5l-9.045-18.09Z");
}

.mek3mhbgb {
  cx: 34.455px;
  cy: 25.642px;
  r: 0.75px;
  fill: currentColor;
}

.of-55_bnc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.337 28.576l-2.319 4.005a.75.75 0 0 1-.933.327l-3.817-1.532q-.23.176-.47.34l-4.079-4.23a5.713 5.713 0 1 0-8.04-4.185L8.854 21.62q.027-.4.079-.798L5.707 18.3a.74.74 0 0 1-.187-.974l3.062-5.29a.75.75 0 0 1 .934-.327l3.83 1.533a11.5 11.5 0 0 1 2.585-1.488l.575-4.039a.746.746 0 0 1 .747-.64h6.14a.746.746 0 0 1 .746.64l.575 4.04a11.7 11.7 0 0 1 2.584 1.487l3.817-1.532a.75.75 0 0 1 .933.327l.706 1.22M21.807 30.868a5.713 5.713 0 0 1-8.04-4.185h0l-5.825-1.681q-.023.344-.026.689a12 12 0 0 0 .104 1.488L4.794 29.7a.74.74 0 0 0-.187.974l3.062 5.29a.75.75 0 0 0 .934.326l3.816-1.532a11.7 11.7 0 0 0 2.584 1.488l.575 4.039a.746.746 0 0 0 .747.64h6.124a.746.746 0 0 0 .747-.64l.575-4.04a11.5 11.5 0 0 0 2.114-1.147Z");
}

.wymuw5w8m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.455 22.785V16.12");
}

</style>
