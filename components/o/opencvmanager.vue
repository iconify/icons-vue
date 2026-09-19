<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ius2dgbmj"/><path class="djktrzb6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:opencvmanager" /></template>
<style>
.djktrzb6s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.72 18.05a4.2 4.2 0 1 1 4.72-.05m-8.81 15.28a4.2 4.2 0 1 1-2.22-3.7m21.59.35a4.15 4.15 0 1 1-4.84-.06M21.72 18.05l-2.58 4.15m-1.49 3.2l-2.24 4.18m13.43-7.32L26.44 18m3.38 7.71l2.37 4.16m4.81.06l2.38-4.16m-17.07 7.51h-4.63");
}

.ius2dgbmj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.14 22.2a8.93 8.93 0 1 1 9.7.06m-6.48 11.02a8.93 8.93 0 1 1-4.71-7.88m21.76.37a8.93 8.93 0 1 1-9.59-.06");
}

</style>
