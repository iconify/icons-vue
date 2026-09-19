<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m8gps9buu"/><path class="ep_xfcc1e"/><path class="z2d7djbrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:note" /></template>
<style>
.ep_xfcc1e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.948 10.55l-13 18.2l-1.5 12.6l11.5-5.3l13.3-18.4a.98.98 0 0 0-.2-1.4l-8.4-6a1.27 1.27 0 0 0-1.7.3");
}

.m8gps9buu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.348 11.35l-3.6-3.6h-20.2v35.8h29.6v-18.7");
}

.z2d7djbrd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.948 36.85a4.4 4.4 0 0 1 3.5 2.6m-2.5-10.7l10 7.3m1.2-22.9l10 7.4m-11.4-5.6l10.1 7.4m-26.6-1.8v-9.5c0-1.4 2.5-1.3 2.5 0v10.7c0 2.5-4.7 2.5-4.7 0V7.45c0-4 5.6-4 5.9 0");
}

</style>
