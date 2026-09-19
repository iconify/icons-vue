<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bjaa6lw9t"/><path class="ajujekb0g"/><circle class="m9d29rbed"/><path class="igeboab-b"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:physics-notes" /></template>
<style>
.ajujekb0g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.77 15.811v3.3a2 2 0 1 1-4 0v-3.3m-5.27-2.697v8m0-3.3a2 2 0 1 1 4 0v3.3");
}

.bjaa6lw9t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.929 21.114v-8h2.619c1.48 0 2.68 1.203 2.68 2.687s-1.2 2.687-2.68 2.687h-2.62m15.842.623v2.7a2 2 0 0 1-3.414 1.415");
}

.igeboab-b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.057 15.814v5.3m-4.882-.447c.365.307.76.448 1.645.448h.448a1.324 1.324 0 0 0 0-2.65h-.897c-.73 0-1.322-.594-1.322-1.325h0c0-.732.592-1.325 1.322-1.325h.449c.885 0 1.28.14 1.645.447m8.203 4.405c.366.307.76.448 1.645.448h.449c.73 0 1.322-.594 1.322-1.325h0c0-.732-.592-1.325-1.322-1.325h-.897c-.73 0-1.323-.594-1.323-1.325h0c0-.732.592-1.325 1.323-1.325h.448c.886 0 1.28.14 1.645.447m-4.688 3.842a2 2 0 0 1-3.737-.992v-1.3a2 2 0 0 1 3.735-.996M11.373 34.888v-8l5.3 8v-8m3.581 8a2 2 0 0 1-2-2v-1.3a2 2 0 1 1 4 0v1.3a2 2 0 0 1-2 2m12.976-.447c.365.307.76.448 1.645.448h.449c.73 0 1.322-.594 1.322-1.325h0c0-.732-.592-1.325-1.322-1.325h-.898c-.73 0-1.322-.594-1.322-1.325h0c0-.732.592-1.325 1.322-1.325h.449c.885 0 1.28.14 1.645.447m-11.64-2.098v6.95m-1.05-5.3h2.1m5.32 4.29a2 2 0 0 1-3.738-.99v-1.3a2 2 0 1 1 4 0v.65h-4");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.m9d29rbed {
  cx: 30.057px;
  cy: 13.364px;
  r: 0.75px;
  fill: currentColor;
}

</style>
