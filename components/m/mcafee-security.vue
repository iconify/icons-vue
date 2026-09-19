<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i68pgbbdx"/><path class="xepbsx3wc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mcafee-security" /></template>
<style>
.i68pgbbdx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.02 34.976V5.5L24 13.024L39.98 5.5v29.476L24 42.5z");
}

.xepbsx3wc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.546 30.71V15.827L24 20.278l9.454-4.451V30.71L24 35.161z");
}

</style>
