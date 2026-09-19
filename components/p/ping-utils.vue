<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cm0_jkbks"/><path class="btbl76b9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ping-utils" /></template>
<style>
.btbl76b9o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.541 5.582h29.048a4.02 4.02 0 0 1 4.006 4.006v29.048a4.02 4.02 0 0 1-4.006 4.007H9.54a4.02 4.02 0 0 1-4.007-4.007V9.588A4.02 4.02 0 0 1 9.54 5.582");
}

.cm0_jkbks {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.829 26.801h9.202v9.202h-9.202zm0-14.804h9.202v9.202h-9.202zm14.389 4.601h9.954m-9.954 14.804h9.954");
}

</style>
