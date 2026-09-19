<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r4k0atbve"/><path class="vzfki6b-y"/><path class="dv-7i71nu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tata-play-binge" /></template>
<style>
.dv-7i71nu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.058 24.823c3.212 1.448 5.442 4.671 5.442 8.408a9.235 9.235 0 0 1-9.237 9.237");
}

.r4k0atbve {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.536h27.763m0-.003a9.235 9.235 0 0 1 9.237 9.236a9.23 9.23 0 0 1-5.442 8.42");
}

.vzfki6b-y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.536v12.31l15.781 6.155L5.5 30.156v12.31l31.561-12.31v-12.31zm0 36.93h27.763");
}

</style>
