<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vz-88pbxp"/><path class="pzn2p8bit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:my-robi" /></template>
<style>
.pzn2p8bit {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.51 35.7L24 27.9l13.51-7.8M24 12.3L10.49 4.5v15.6M24 12.3v31.2");
}

.vz-88pbxp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.49 35.7L24 27.9l-13.51-7.8L24 12.3l13.51 7.8v15.6L24 43.5z");
}

</style>
