<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ulztkdbrc"/><path class="igy0zughn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:simplelauncher" /></template>
<style>
.igy0zughn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 23.699L24 8.781l18.5 14.918");
}

.ulztkdbrc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.868 14.75v24.47h8.952v-8.953h8.356v8.952h8.952V19.526");
}

</style>
