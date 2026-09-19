<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gjff_s-nv"/><path class="bota09b8c"/><path class="o4_69eb3l"/><path class="tmlii1b-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mbin" /></template>
<style>
.bota09b8c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.164 34.948L24 16.178l10.836 18.77");
}

.gjff_s-nv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.747 34.948h10.836l2.709-4.693L24 34.948l2.71-4.693l2.708 4.693h10.836");
}

.o4_69eb3l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 7.839c-.372 0-.716.199-.902.521L5.64 38.597a1.043 1.043 0 0 0 .904 1.564h34.912a1.043 1.043 0 0 0 .904-1.564L24.902 8.36A1.04 1.04 0 0 0 24 7.84");
}

.tmlii1b-u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.567 25.063a1 1 0 0 0 0 1L24 30.277l2.433-4.214a1 1 0 0 0 0-1L24 20.849z");
}

</style>
