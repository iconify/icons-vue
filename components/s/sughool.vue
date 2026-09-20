<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oxg9c0ban"/><path class="pfndhyobm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sughool" /></template>
<style>
.oxg9c0ban {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 30.5h-13v-13h-13v13h-13");
}

.pfndhyobm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.298 26.298L24 24v-3.25m11.389-2.264a5.5 5.5 0 0 1 0 7.778m-22.778 0a5.5 5.5 0 0 1 0-7.778m2.061 6.717a4 4 0 0 1 0-5.657m18.656.001a4 4 0 0 1 0 5.657");
}

</style>
