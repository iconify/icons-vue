<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="esc39qbep"/><path class="uz5sxlb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:monitormix" /></template>
<style>
.esc39qbep {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.203 19.384A15.5 15.5 0 0 1 24 8.5c8.068 0 14.786 6.188 15.448 14.228m-.889 6.59A15.5 15.5 0 0 1 24 39.5c-8.422 0-15.303-6.725-15.496-15.145");
}

.uz5sxlb-s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 26.5v-9l9 9l9-9v9m3 4v-9l9 9l9-9v9");
}

</style>
