<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="je5s7xbuz"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:upstox" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.je5s7xbuz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.23 22.579v2.765a4.73 4.73 0 0 0 4.732 4.731h0a4.73 4.73 0 0 0 4.73-4.73v-7.807m0 7.806v4.731m5.346-4.731a4.73 4.73 0 0 0 4.731 4.731h0a4.73 4.73 0 0 0 4.731-4.73v-3.076a4.73 4.73 0 0 0-4.73-4.73h0a4.73 4.73 0 0 0-4.732 4.73m0-4.731v18.924M7.5 22.27a4.73 4.73 0 0 0 4.73-4.732");
}

</style>
