<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kcs6h0bjv"/><path class="z-jt85lwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:serenity" /></template>
<style>
.kcs6h0bjv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.022 12.242a14.4 14.4 0 0 0-5.478 11.26A14.4 14.4 0 0 0 24 34.745a14.4 14.4 0 0 0 5.455-11.243a14.4 14.4 0 0 0-5.433-11.26");
}

.z-jt85lwn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.42 18.218a14.4 14.4 0 0 1 6.85-2.95a14.4 14.4 0 0 1-.924 12.47A14.4 14.4 0 0 1 24 34.746a14.4 14.4 0 0 0 12.465-.897A14.4 14.4 0 0 0 43.5 23.514a14.4 14.4 0 0 0-7.387-.875M19.58 18.218a14.4 14.4 0 0 0-6.85-2.95a14.4 14.4 0 0 0 .924 12.47A14.4 14.4 0 0 0 24 34.746a14.4 14.4 0 0 1-12.465-.897A14.4 14.4 0 0 1 4.5 23.514a14.4 14.4 0 0 1 7.387-.875");
}

</style>
