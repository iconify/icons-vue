<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j2-392war"/><circle class="d7yi_mb3x"/><circle class="gfcnr9baa"/><path class="ttsso-bur"/><circle class="afo-abbfz"/><circle class="djkanpb0o"/><path class="t_6xvyu1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:monocles-chat" /></template>
<style>
.afo-abbfz {
  cx: 17.174px;
  cy: 19.381px;
  r: 3.742px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.d7yi_mb3x {
  cx: 30.826px;
  cy: 19.381px;
  r: 3.742px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.djkanpb0o {
  cx: 10.578px;
  cy: 19.381px;
  r: 0.75px;
  fill: currentColor;
}

.gfcnr9baa {
  cx: 37.423px;
  cy: 19.381px;
  r: 0.75px;
  fill: currentColor;
}

.j2-392war {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.004 27.816s1.342-1.052 2.164-.65c2.756 1.347 3.96 5.414 9.71 2.302c-3.924 7.14-10.172 4.097-11.874 1.598c-1.701 2.5-7.95 5.541-11.873-1.598c5.749 3.112 6.954-.955 9.71-2.303c.821-.401 2.163.651 2.163.651m13.419-.473v-4.941");
}

.t_6xvyu1j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.5 24C2.5 12.126 12.126 2.5 24 2.5S45.5 12.126 45.5 24S35.874 45.5 24 45.5a21.6 21.6 0 0 1-10.327-2.637l-9.638 1.102l1.102-9.638A21.6 21.6 0 0 1 2.5 24");
}

.ttsso-bur {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.578 27.343v-4.941");
}

</style>
