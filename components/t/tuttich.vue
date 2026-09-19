<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kzhp1wgwb"/><path class="wat6mjbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tuttich" /></template>
<style>
.kzhp1wgwb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.738 4.667a4.216 4.216 0 0 0-5.22 2.881q0 0 0 0L4.666 31.263a4.216 4.216 0 0 0 2.882 5.22l23.714 6.852a4.216 4.216 0 0 0 5.22-2.882q0 0 0 0l6.85-23.714a4.216 4.216 0 0 0-2.88-5.22h-.001z");
}

.wat6mjbfv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.62 38.868a5.27 5.27 0 0 1-8.997-3.726v-18.52m0 6.324H24");
}

</style>
