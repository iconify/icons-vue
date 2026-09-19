<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gc72olbul"/><circle class="t4_e5i6vd"/><path class="lyq5srm5k"/><circle class="or1-14wwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:moovit" /></template>
<style>
.gc72olbul {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 43.5s15.496-12.013 15.496-23.504a15.496 15.496 0 0 0-30.992 0C8.504 31.487 24 43.5 24 43.5");
}

.lyq5srm5k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.75 22.322A8 8 0 0 1 24 24a8 8 0 0 1-4.75-1.678");
}

.or1-14wwl {
  cx: 30.797px;
  cy: 18.555px;
  r: 0.75px;
  fill: currentColor;
}

.t4_e5i6vd {
  cx: 17.203px;
  cy: 18.555px;
  r: 0.75px;
  fill: currentColor;
}

</style>
