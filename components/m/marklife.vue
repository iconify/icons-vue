<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ymhk46b2w"/><path class="h1a1_x2nw"/><path class="u_e9z490b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:marklife" /></template>
<style>
.h1a1_x2nw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.635 22.628h-13.43a2.11 2.11 0 0 0-2.107 2.108v8.887c0 1.164.944 2.108 2.108 2.108h13.429a2.11 2.11 0 0 0 2.108-2.108v-8.887a2.11 2.11 0 0 0-2.108-2.108m-26.108-2.02h38.75m-17.024-6.745h-4.665a2.11 2.11 0 0 0-2.108 2.108v.92c0 1.164.944 2.108 2.108 2.108h4.664a2.11 2.11 0 0 0 2.109-2.108v-.92a2.11 2.11 0 0 0-2.108-2.108");
}

.u_e9z490b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.82 33.382v-8.35l2.755 5.509L24 33.39l4.18-8.347v8.347");
}

.ymhk46b2w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.495 20.75v7.029l-5.887-.016A2.11 2.11 0 0 1 4.5 25.655V14.377c0-1.164.944-2.108 2.108-2.108h34.784c1.164 0 2.108.944 2.108 2.108v11.278a2.11 2.11 0 0 1-2.108 2.108l-6.278.022l-.019-7.035");
}

</style>
